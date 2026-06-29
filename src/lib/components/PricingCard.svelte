<!-- PricingCard Component -->
<script>
  let { planName, price, features = [], isPopular = false } = $props();
</script>

<div class={`p-8 rounded-lg flex flex-col ${isPopular ? 'bg-gray-900 text-white border-2 border-gray-700 transform scale-105 shadow-2xl' : 'bg-white text-black border border-gray-200 shadow-md'}`}>
  {#if isPopular}
    <div class="bg-white text-black text-xs font-bold uppercase py-1 px-3 rounded-full self-start mb-4">Most Popular</div>
  {/if}
  <h3 class="text-2xl font-bold mb-2">{planName}</h3>
  <div class="text-4xl font-extrabold mb-6">${price}</div>
  <ul class="space-y-3 mb-8 flex-1">
    {#each features as feature}
      <li class="flex items-start">
        <svg class={`w-5 h-5 mr-2 ${isPopular ? 'text-gray-300' : 'text-gray-700'}`} fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
        <span class="text-sm">{feature}</span>
      </li>
    {/each}
  </ul>
  <button class={`w-full py-3 font-bold rounded transition-colors cursor-pointer ${isPopular ? 'bg-white text-black hover:bg-gray-200' : 'bg-black text-white hover:bg-gray-800'}`}>
    Select Plan
  </button>
</div>