<script>
  const logos = [
    { name: "granola", font: "font-serif font-bold" },
    { name: "CURSOR", font: "font-mono font-bold tracking-widest" },
    { name: "Raycast", font: "font-sans font-bold" },
    { name: "n8n", font: "font-mono font-bold text-xl" },
    { name: "Ashby", font: "font-sans font-bold italic" },
    { name: "Buildkite", font: "font-sans font-bold text-green-600" },
    { name: "Laravel", font: "font-sans font-light uppercase tracking-widest text-red-500" },
    { name: "Stytch", font: "font-sans font-bold tracking-tight" },
    { name: "tinybird", font: "font-mono font-bold text-blue-500" },
    { name: "Vapi", font: "font-sans font-black tracking-tighter" },
    { name: "tines", font: "font-sans font-bold" },
    { name: "Default", font: "font-serif italic font-bold" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Hundreds of fast-moving teams rely on Plain
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
