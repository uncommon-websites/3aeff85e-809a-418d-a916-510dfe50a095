<script>
    // Icons replaced with CSS shapes for pixel-perfect custom visuals
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                A Digital Platform Built for<br />Modern Private Markets
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Digital Platform -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Fully Digital Process</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-4">
                        {#each [1, 2, 3, 4, 5, 6] as i}
                            <div class="h-10 w-10 bg-white rounded-full shadow-sm flex items-center justify-center text-gray-400">
                                <div class="h-4 w-4 bg-primary-200 rounded-sm"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    From deal selection to onboarding, monitoring, and reporting—everything is digital. No paperwork, secure transactions, and seamless user experience with dedicated advisor support.
                </p>
            </div>

            <!-- Deal Transparency -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Deal-Level Transparency</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px] space-y-2">
                        <div class="h-2 bg-primary-100 rounded w-1/3 mb-4"></div>
                        {#each [1, 2, 3, 4, 5] as i}
                            <div class="flex items-center gap-2">
                                <div class="h-2 w-2 rounded-full bg-primary-200"></div>
                                <div class="h-1.5 bg-gray-100 rounded w-3/4"></div>
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Complete visibility into every investment with granular reporting, real-time portfolio monitoring, and detailed performance analytics for institutional clients.
                </p>
            </div>

            <!-- Dedicated Support -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Dedicated Advisors</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="flex -space-x-2">
                        <div class="h-10 w-10 rounded-full bg-primary-100 border-2 border-white flex items-center justify-center text-primary-600 text-xs">Z</div>
                        <div class="h-10 w-10 rounded-full bg-primary-100 border-2 border-white flex items-center justify-center text-primary-600 text-xs">N</div>
                        <div class="h-10 w-10 rounded-full bg-primary-100 border-2 border-white flex items-center justify-center text-primary-600 text-xs">H</div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Personalized guidance from dedicated advisors with deep private markets expertise. Support throughout your entire investment journey.
                </p>
            </div>

            <!-- Curated Selection -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Highly Selective (4%)</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="relative">
                        <!-- Tree structure visualization -->
                        <div class="flex justify-center gap-4 mb-4">
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                            <div class="h-6 w-6 border border-gray-300 bg-white rounded-sm"></div>
                        </div>
                        <div class="flex justify-center mb-4">
                            <div class="h-8 w-px bg-gray-300"></div>
                        </div>
                        <div class="flex justify-center">
                            <div class="h-8 w-8 bg-primary-800 rounded flex items-center justify-center text-white text-xs">✓</div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Only 4% of opportunities from trusted partners meet our rigorous selection criteria. This disciplined approach has delivered consistent positive returns over eight years.
                </p>
            </div>

            <!-- Lower Minimums -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Accessible Minimums</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="bg-white p-4 rounded shadow-sm w-full max-w-[200px]">
                        <div class="flex justify-between mb-4">
                            <div class="text-[10px] font-bold text-gray-500">MIN</div>
                            <div class="text-lg font-bold text-primary-700">$150K</div>
                        </div>
                        <div class="space-y-2">
                            <div class="h-px bg-gray-100 w-full"></div>
                            <div class="h-1.5 bg-primary-100 rounded w-1/2"></div>
                            <div class="h-1.5 bg-primary-100 rounded w-3/4"></div>
                            <div class="h-1.5 bg-primary-100 rounded w-2/3"></div>
                        </div>
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Access institutional-grade investments with minimum thresholds starting at $150,000. Democratizing private markets for high-net-worth individuals and advisors.
                </p>
            </div>

            <!-- Bankable Products -->
            <div class="bg-gray-50 p-8 rounded-lg flex flex-col h-full">
                <h3 class="text-lg font-serif text-gray-900 mb-8">Bankable Products</h3>
                <div class="flex-1 flex items-center justify-center mb-8">
                    <div class="grid grid-cols-3 gap-1">
                        {#each [1, 2, 3, 4, 5, 6, 7, 8, 9] as i}
                            <div class={`h-8 w-8 border border-gray-200 ${i === 5 ? 'bg-primary-800 flex items-center justify-center' : 'bg-white'}`}>
                                {#if i === 5}
                                    <div class="h-2 w-2 bg-white rounded-full"></div>
                                {/if}
                            </div>
                        {/each}
                    </div>
                </div>
                <p class="text-xs text-gray-500 leading-relaxed mt-auto">
                    Products structured with ISINs for seamless integration with existing banking platforms. Institutions maintain full control within their systems.
                </p>
            </div>
        </div>
    </div>
</section>
