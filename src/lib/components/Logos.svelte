<script>
  const logos = [
    { name: "Typeform", font: "font-sans font-bold" },
    { name: "Webflow", font: "font-sans font-bold" },
    { name: "Airtable", font: "font-sans font-bold" },
    { name: "Notion", font: "font-serif font-bold" },
    { name: "Zapier", font: "font-sans font-bold" },
    { name: "Google Sheets", font: "font-sans font-medium" },
    { name: "Tally", font: "font-sans font-bold" },
    { name: "Framer", font: "font-sans font-bold" },
    { name: "HubSpot", font: "font-sans font-bold" },
    { name: "Slack", font: "font-sans font-bold" },
    { name: "PostgreSQL", font: "font-mono font-bold" },
    { name: "MongoDB", font: "font-sans font-bold" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Integrates with your favorite tools
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
