<script>
  // Hero component
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 overflow-hidden">
  <div class="container-custom flex flex-col items-center text-center">
    
    <!-- Badge -->
    <a href="#" class="inline-flex items-center gap-1 px-3 py-1 rounded-full bg-green-50 border border-green-100 text-green-600 text-xs font-medium mb-8 hover:bg-green-100 transition-colors">
      Now available on Shopify App Store
      <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
    </a>

    <!-- Headline -->
    <h1 class="text-5xl md:text-7xl font-bold tracking-tight text-gray-900 mb-6 max-w-4xl mx-auto leading-[1.1]">
      Recover shipping costs <br class="hidden md:block" /> <span class="text-plain-green">automatically</span>
    </h1>

    <!-- Subheadline -->
    <p class="text-lg md:text-xl text-gray-500 mb-10 max-w-2xl mx-auto leading-relaxed">
      Claimable automates carrier claim filing and tracking, recovering your shipping costs without the manual work. Connect your Shopify store and start claiming refunds in minutes.
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
            app.claimable.co/claims
          </div>
        </div>
      </div>

      <!-- App Interface Mockup -->
      <div class="flex h-[500px] md:h-[600px] text-left bg-white">
        <!-- Sidebar -->
        <div class="w-16 md:w-64 border-r border-gray-100 bg-gray-50/50 p-4 hidden md:flex flex-col gap-4">
            <div class="flex items-center gap-2 mb-4">
                <div class="w-6 h-6 rounded bg-plain-green/20"></div>
                <div class="h-3 w-20 bg-gray-200 rounded"></div>
            </div>
            <div class="flex items-center gap-3 p-2 rounded bg-green-50 border-l-2 border-plain-green">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18"/><path d="M9 21V9"/></svg>
                <div class="h-2 w-24 bg-gray-300 rounded"></div>
            </div>
            <div class="flex items-center gap-3 p-2 rounded hover:bg-gray-100">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" x2="12" y1="15" y2="3"/></svg>
                <div class="h-2 w-24 bg-gray-100 rounded"></div>
            </div>
            <div class="flex items-center gap-3 p-2 rounded hover:bg-gray-100">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 3v18h18"/><path d="m19 9-5 5-4-4-3 3"/></svg>
                <div class="h-2 w-24 bg-gray-100 rounded"></div>
            </div>
            <div class="flex items-center gap-3 p-2 rounded hover:bg-gray-100">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="3"/><path d="M12 1v6m0 6v6M5.6 5.6l4.2 4.2m4.4 4.4l4.2 4.2M1 12h6m6 0h6M5.6 18.4l4.2-4.2m4.4-4.4l4.2-4.2"/></svg>
                <div class="h-2 w-24 bg-gray-100 rounded"></div>
            </div>
        </div>

        <!-- Main Content -->
        <div class="flex-1 flex flex-col">
            <!-- Header -->
            <div class="h-14 border-b border-gray-100 flex items-center px-6 justify-between">
                <div class="flex items-center gap-3">
                    <h2 class="text-lg font-bold text-gray-900">Active Claims</h2>
                    <span class="px-2 py-0.5 bg-green-100 text-green-700 text-xs font-bold rounded">24 Pending</span>
                </div>
                <div class="flex items-center gap-2">
                    <button class="px-3 py-1.5 text-xs font-semibold border border-gray-200 rounded text-gray-700 hover:border-gray-400 transition-colors">
                        Filter
                    </button>
                </div>
            </div>
            <!-- Claims List -->
            <div class="flex-1 p-6 bg-white relative overflow-auto">
                <!-- Claims Table Header -->
                <div class="grid grid-cols-12 gap-4 text-xs font-bold text-gray-500 uppercase tracking-wide mb-4 pb-2 border-b border-gray-100">
                    <div class="col-span-3">Tracking #</div>
                    <div class="col-span-2">Carrier</div>
                    <div class="col-span-2">Issue</div>
                    <div class="col-span-2">Amount</div>
                    <div class="col-span-2">Status</div>
                    <div class="col-span-1">Date</div>
                </div>

                <!-- Claim Row 1 -->
                <div class="grid grid-cols-12 gap-4 items-center py-3 border-b border-gray-50 hover:bg-gray-50 cursor-pointer">
                    <div class="col-span-3 text-sm font-mono text-gray-900">1Z999AA10123456784</div>
                    <div class="col-span-2 flex items-center gap-2">
                        <div class="w-6 h-6 rounded bg-amber-100 flex items-center justify-center text-xs font-bold text-amber-700">U</div>
                        <span class="text-sm text-gray-700">UPS</span>
                    </div>
                    <div class="col-span-2 text-sm text-gray-700">Late Delivery</div>
                    <div class="col-span-2 text-sm font-bold text-gray-900">$47.50</div>
                    <div class="col-span-2">
                        <span class="px-2 py-1 bg-green-100 text-green-700 text-xs font-bold rounded">Approved</span>
                    </div>
                    <div class="col-span-1 text-xs text-gray-500">2d ago</div>
                </div>

                <!-- Claim Row 2 -->
                <div class="grid grid-cols-12 gap-4 items-center py-3 border-b border-gray-50 hover:bg-gray-50 cursor-pointer">
                    <div class="col-span-3 text-sm font-mono text-gray-900">9400111899223344556677</div>
                    <div class="col-span-2 flex items-center gap-2">
                        <div class="w-6 h-6 rounded bg-blue-100 flex items-center justify-center text-xs font-bold text-blue-700">U</div>
                        <span class="text-sm text-gray-700">USPS</span>
                    </div>
                    <div class="col-span-2 text-sm text-gray-700">Damaged</div>
                    <div class="col-span-2 text-sm font-bold text-gray-900">$124.00</div>
                    <div class="col-span-2">
                        <span class="px-2 py-1 bg-yellow-100 text-yellow-700 text-xs font-bold rounded">Pending</span>
                    </div>
                    <div class="col-span-1 text-xs text-gray-500">5d ago</div>
                </div>

                <!-- Claim Row 3 -->
                <div class="grid grid-cols-12 gap-4 items-center py-3 border-b border-gray-50 hover:bg-gray-50 cursor-pointer">
                    <div class="col-span-3 text-sm font-mono text-gray-900">794612345678</div>
                    <div class="col-span-2 flex items-center gap-2">
                        <div class="w-6 h-6 rounded bg-purple-100 flex items-center justify-center text-xs font-bold text-purple-700">F</div>
                        <span class="text-sm text-gray-700">FedEx</span>
                    </div>
                    <div class="col-span-2 text-sm text-gray-700">Lost Package</div>
                    <div class="col-span-2 text-sm font-bold text-gray-900">$89.99</div>
                    <div class="col-span-2">
                        <span class="px-2 py-1 bg-blue-100 text-blue-700 text-xs font-bold rounded">Filed</span>
                    </div>
                    <div class="col-span-1 text-xs text-gray-500">1w ago</div>
                </div>
            </div>
            
            <!-- Action Bar -->
            <div class="h-16 border-t border-gray-100 px-6 flex items-center justify-between gap-4">
                 <div class="text-sm text-gray-600">
                    Showing <span class="font-bold">3</span> of <span class="font-bold">24</span> active claims
                 </div>
                 <button class="px-4 py-2 bg-plain-green text-white text-sm font-bold rounded hover:opacity-90 transition-opacity">
                    View All Claims
                 </button>
            </div>
        </div>

        <!-- Right Sidebar -->
        <div class="w-72 border-l border-gray-100 bg-white p-4 hidden lg:block">
            <div class="space-y-6">
                <div>
                    <h3 class="text-xs font-bold text-gray-900 uppercase tracking-wide mb-3">Recovery Stats</h3>
                    <div class="space-y-3">
                        <div class="flex justify-between items-center">
                            <span class="text-sm text-gray-600">This Month</span>
                            <span class="text-sm font-bold text-gray-900">$2,847</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-sm text-gray-600">Success Rate</span>
                            <span class="text-sm font-bold text-green-600">94%</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <span class="text-sm text-gray-600">Avg. Time</span>
                            <span class="text-sm font-bold text-gray-900">3.2 days</span>
                        </div>
                    </div>
                </div>
                <hr class="border-gray-100"/>
                <div>
                    <h3 class="text-xs font-bold text-gray-900 uppercase tracking-wide mb-3">Quick Actions</h3>
                    <div class="space-y-2">
                        <button class="w-full px-3 py-2 bg-gray-50 border border-gray-200 rounded text-xs font-medium text-gray-700 hover:bg-gray-100 transition-colors text-left">
                            File New Claim
                        </button>
                        <button class="w-full px-3 py-2 bg-gray-50 border border-gray-200 rounded text-xs font-medium text-gray-700 hover:bg-gray-100 transition-colors text-left">
                            Export Report
                        </button>
                        <button class="w-full px-3 py-2 bg-gray-50 border border-gray-200 rounded text-xs font-medium text-gray-700 hover:bg-gray-100 transition-colors text-left">
                            View Analytics
                        </button>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</section>
