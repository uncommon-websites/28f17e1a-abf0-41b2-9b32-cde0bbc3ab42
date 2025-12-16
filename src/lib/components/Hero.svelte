<script>
  // Hero component
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 overflow-hidden">
  <div class="container-custom flex flex-col items-center text-center">
    
    <!-- Badge -->
    <a href="#" class="inline-flex items-center gap-1 px-3 py-1 rounded-full bg-green-50 border border-green-100 text-green-600 text-xs font-medium mb-8 hover:bg-green-100 transition-colors">
      Backed by Lightspeed & Xavier Niel • €5M raised
      <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
    </a>

    <!-- Headline -->
    <h1 class="text-5xl md:text-7xl font-bold tracking-tight text-gray-900 mb-6 max-w-4xl mx-auto leading-[1.1]">
      Turn phone chaos <br class="hidden md:block" /> into <span class="text-plain-green">closed deals</span>
    </h1>

    <!-- Subheadline -->
    <p class="text-lg md:text-xl text-gray-500 mb-10 max-w-2xl mx-auto leading-relaxed">
      AI-powered phone system built for small sales teams. Handle calls professionally, sync to CRM instantly, and close more deals—all from your mobile.
    </p>

    <!-- Buttons -->
    <div class="flex flex-col sm:flex-row items-center gap-4 mb-20">
      <a href="#" class="px-6 py-3 text-sm font-bold bg-plain-green text-white rounded hover:opacity-90 transition-opacity uppercase tracking-wide shadow-sm shadow-green-200">
        Start Free Trial
      </a>
      <a href="#" class="px-6 py-3 text-sm font-bold border border-gray-200 text-gray-700 rounded hover:border-gray-400 transition-colors uppercase tracking-wide bg-white">
        See How It Works
      </a>
    </div>

    <!-- Hero Image / UI Mockup -->
    <div class="relative w-full max-w-5xl mx-auto rounded-xl shadow-2xl border border-gray-200 bg-white overflow-hidden perspective-1000">
      <!-- Browser Chrome -->
      <div class="bg-gray-50 border-b border-gray-200 px-4 py-3 flex items-center gap-2">
        <div class="flex gap-1.5">
          <div class="w-3 h-3 rounded-full bg-red-400"></div>
          <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
          <div class="w-3 h-3 rounded-full bg-green-400"></div>
        </div>
        <div class="flex-1 text-center">
          <div class="inline-flex items-center justify-center px-3 py-0.5 rounded bg-white border border-gray-200 text-[10px] text-gray-400 font-mono shadow-sm">
            app.allo.io
          </div>
        </div>
      </div>

      <!-- App Interface Mockup -->
      <div class="flex h-[500px] md:h-[600px] text-left bg-white">
        <!-- Sidebar -->
        <div class="w-16 md:w-64 border-r border-gray-100 bg-gray-50/50 p-4 hidden md:flex flex-col gap-4">
            <div class="flex items-center gap-2 mb-4">
                <div class="w-6 h-6 rounded bg-gray-200"></div>
                <div class="h-3 w-20 bg-gray-200 rounded"></div>
            </div>
            {#each [1, 2, 3, 4, 5] as i}
            <div class="flex items-center gap-3 p-2 rounded hover:bg-gray-100">
                <div class="w-4 h-4 rounded bg-gray-200"></div>
                <div class="h-2 w-24 bg-gray-100 rounded"></div>
            </div>
            {/each}
        </div>

        <!-- Main Content -->
        <div class="flex-1 flex flex-col">
            <!-- Header -->
            <div class="h-14 border-b border-gray-100 flex items-center px-6 justify-between">
                <div class="flex items-center gap-3">
                    <div class="w-8 h-8 rounded-full bg-orange-100 flex items-center justify-center text-orange-600 font-bold text-xs">AA</div>
                    <div>
                        <div class="h-3 w-32 bg-gray-200 rounded mb-1"></div>
                        <div class="h-2 w-20 bg-gray-100 rounded"></div>
                    </div>
                </div>
            </div>
            <!-- Chat Area -->
            <div class="flex-1 p-6 bg-white relative">
                <!-- Message -->
                <div class="flex gap-4 mb-6">
                    <div class="w-8 h-8 rounded-full bg-gray-200 flex-shrink-0"></div>
                    <div class="flex-1">
                        <div class="flex items-center gap-2 mb-1">
                            <div class="h-3 w-24 bg-gray-200 rounded"></div>
                            <div class="h-2 w-12 bg-gray-100 rounded"></div>
                        </div>
                        <div class="h-2 w-full max-w-md bg-gray-100 rounded mb-2"></div>
                        <div class="h-2 w-full max-w-sm bg-gray-100 rounded"></div>
                    </div>
                </div>

                <!-- AI Call Summary Box -->
                <div class="bg-[#F2FBF7] rounded-lg p-6 shadow-xl border border-green-100 max-w-2xl mx-auto mt-8">
                    <div class="flex items-center justify-between mb-4 border-b border-green-200 pb-3">
                        <div class="flex items-center gap-2 text-xs font-bold text-gray-700">
                            <div class="w-5 h-5 rounded-full bg-plain-green flex items-center justify-center text-white">
                                <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
                            </div>
                            AI Call Summary
                        </div>
                        <div class="text-[10px] text-gray-500 bg-white px-2 py-1 rounded">Just now</div>
                    </div>
                    <div class="space-y-2 mb-4 text-sm text-gray-700">
                        <p><span class="font-bold">Caller:</span> Sarah Johnson • Demo request</p>
                        <p><span class="font-bold">Duration:</span> 3m 42s</p>
                        <p class="text-xs leading-relaxed pt-2 border-t border-green-100">"Interested in upgrading to Business plan. Currently using competitor. Needs team of 5. Follow up with pricing."</p>
                    </div>
                    <div class="flex gap-2">
                        <button class="flex-1 bg-plain-green text-white text-xs font-bold py-2 rounded hover:opacity-90">Sync to CRM</button>
                        <button class="px-3 bg-white border border-gray-200 text-xs font-bold rounded hover:bg-gray-50">View Details</button>
                    </div>
                </div>
            </div>
            
            <!-- Reply Box -->
            <div class="h-16 border-t border-gray-100 px-6 flex items-center gap-4">
                 <div class="flex-1 h-10 bg-gray-50 rounded border border-gray-200"></div>
                 <div class="w-20 h-10 bg-plain-green rounded opacity-20"></div>
            </div>
        </div>

        <!-- Right Sidebar -->
        <div class="w-72 border-l border-gray-100 bg-white p-4 hidden lg:block">
            <div class="space-y-6">
                <div>
                    <div class="h-3 w-20 bg-gray-200 rounded mb-3"></div>
                    <div class="space-y-2">
                        <div class="flex justify-between"><div class="h-2 w-16 bg-gray-100 rounded"></div><div class="h-2 w-12 bg-gray-100 rounded"></div></div>
                        <div class="flex justify-between"><div class="h-2 w-16 bg-gray-100 rounded"></div><div class="h-2 w-12 bg-gray-100 rounded"></div></div>
                        <div class="flex justify-between"><div class="h-2 w-16 bg-gray-100 rounded"></div><div class="h-2 w-12 bg-gray-100 rounded"></div></div>
                    </div>
                </div>
                <hr class="border-gray-100"/>
                <div>
                    <div class="h-3 w-20 bg-gray-200 rounded mb-3"></div>
                    <div class="flex gap-2 flex-wrap">
                        <div class="h-6 w-16 bg-gray-50 border border-gray-200 rounded-full"></div>
                        <div class="h-6 w-20 bg-gray-50 border border-gray-200 rounded-full"></div>
                        <div class="h-6 w-12 bg-gray-50 border border-gray-200 rounded-full"></div>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</section>
