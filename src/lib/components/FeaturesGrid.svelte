<section class="py-12 bg-plain-dark">
  <div class="container-custom">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      
      <!-- Card 1 -->
      <div class="bg-plain-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex items-center justify-center relative">
            <!-- Form Icons Grid -->
            <div class="grid grid-cols-4 gap-3 opacity-60 group-hover:opacity-100 transition-opacity">
                {#each Array(8) as _}
                <div class="w-8 h-8 rounded bg-gray-800 border border-gray-700 flex items-center justify-center">
                  <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-gray-600"><rect x="3" y="3" width="18" height="18" rx="2"/><line x1="9" y1="9" x2="15" y2="9"/><line x1="9" y1="15" x2="15" y2="15"/></svg>
                </div>
                {/each}
            </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Connect any form platform</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Typeform, Google Forms, Webflow, Tally, and more. One-click integrations that sync submissions in real-time to your database.
        </p>
      </div>

      <!-- Card 2 -->
      <div class="bg-plain-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex items-center justify-center">
            <!-- Field Mapping Visual -->
            <div class="space-y-2 w-full">
                <div class="flex items-center gap-2">
                    <div class="flex-1 h-6 bg-gray-800 rounded"></div>
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-green-500"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
                    <div class="flex-1 h-6 bg-green-900/40 rounded"></div>
                </div>
                <div class="flex items-center gap-2">
                    <div class="flex-1 h-6 bg-gray-800 rounded"></div>
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-green-500"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
                    <div class="flex-1 h-6 bg-green-900/40 rounded"></div>
                </div>
                <div class="flex items-center gap-2">
                    <div class="flex-1 h-6 bg-gray-800 rounded"></div>
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-green-500"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
                    <div class="flex-1 h-6 bg-green-900/40 rounded"></div>
                </div>
            </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Intelligent field mapping</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          AI-powered parsing automatically maps form fields to your database schema. No manual configuration, just instant structured data.
        </p>
      </div>

      <!-- Card 3 -->
      <div class="bg-plain-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex flex-col items-center justify-center gap-3">
             <div class="flex gap-2">
                 <div class="px-3 py-1 bg-green-600 text-white text-xs rounded font-medium">Clean data</div>
                 <div class="px-3 py-1 bg-green-600/20 text-green-400 border border-green-600/30 text-xs rounded font-medium">Validate</div>
             </div>
             <div class="flex gap-2">
                 <div class="px-3 py-1 bg-green-600/20 text-green-400 border border-green-600/30 text-xs rounded font-medium">Transform</div>
                 <div class="px-3 py-1 bg-green-600/20 text-green-400 border border-green-600/30 text-xs rounded font-medium">Export</div>
             </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">No-code simplicity</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Set up in minutes, not weeks. Visual interface for data transformation, validation rules, and export configurations. Zero coding required.
        </p>
      </div>

    </div>
  </div>
</section>
