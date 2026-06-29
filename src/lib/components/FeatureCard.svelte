<!-- FeatureCard Component -->
<script>
  let { title, description, icon = null } = $props();
</script>

<div class="bg-white p-8 rounded-lg text-center flex flex-col items-center shadow-md border border-gray-100 hover:shadow-lg transition-shadow">
  {#if icon}
    <div class="mb-4">
      {@html icon}
    </div>
  {/if}
  <h3 class="text-xl font-bold mb-3 text-black">{title}</h3>
  <p class="text-gray-600 text-sm leading-relaxed">
    {description}
  </p>
</div>