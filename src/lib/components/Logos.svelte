<script>
  const logos = [
    { name: "Allbirds", font: "font-sans font-bold" },
    { name: "MVMT", font: "font-sans font-black tracking-wider" },
    { name: "Bombas", font: "font-sans font-bold" },
    { name: "Chubbies", font: "font-sans font-bold italic" },
    { name: "Pura Vida", font: "font-serif font-bold" },
    { name: "LARQ", font: "font-sans font-black tracking-widest" },
    { name: "Brooklinen", font: "font-sans font-light tracking-wide" },
    { name: "Huckberry", font: "font-sans font-bold" },
    { name: "Outdoor Voices", font: "font-sans font-medium" },
    { name: "Casper", font: "font-sans font-bold tracking-tight" },
    { name: "Warby Parker", font: "font-serif font-bold" },
    { name: "Glossier", font: "font-sans font-light italic" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Trusted by high-volume Shopify merchants
    </p>
    
    <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-x-8 gap-y-12 items-center justify-items-center opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
      {#each logos as logo}
        <div class="text-xl md:text-2xl text-gray-800 flex items-center justify-center w-full">
           <!-- Placeholder for actual SVG logos -->
           <span class="{logo.font}">{logo.name}</span>
        </div>
      {/each}
    </div>
  </div>
</section>
