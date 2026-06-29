<!-- SectionWrapper Component -->
<script>
  let { theme = 'dark' } = $props(); // 'dark' | 'light' | 'gray'

  const themes = {
    dark: 'bg-black text-white',
    light: 'bg-white text-black',
    gray: 'bg-gray-100 text-black'
  };
</script>

<section class="{themes[theme]} py-16 px-4 sm:px-6 lg:px-8 flex justify-center">
  <div class="max-w-6xl w-full">
    <slot />
  </div>
</section>