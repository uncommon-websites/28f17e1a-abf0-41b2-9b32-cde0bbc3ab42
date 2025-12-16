<script>
  const logos = [
    { name: "Asphalte", font: "font-sans font-bold" },
    { name: "Compas", font: "font-sans font-bold tracking-tight" },
    { name: "Spendesk", font: "font-sans font-bold" },
    { name: "SAFTI", font: "font-sans font-bold tracking-widest" },
    { name: "Le Wagon", font: "font-sans font-medium" },
    { name: "Keep Cool", font: "font-sans font-bold" },
    { name: "Morning", font: "font-serif font-bold italic" },
    { name: "Progression", font: "font-sans font-bold tracking-tight" },
    { name: "Matchers", font: "font-sans font-bold" },
    { name: "Atout Pret", font: "font-sans font-medium" },
    { name: "Klimb", font: "font-sans font-black tracking-tighter" },
    { name: "Hyperline", font: "font-sans font-bold" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      7,000+ small businesses trust Allo across three continents
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
