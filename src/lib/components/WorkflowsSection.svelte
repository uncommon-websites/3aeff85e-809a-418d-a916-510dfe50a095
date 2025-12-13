<script>
    import { Check, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Three Core Investment<br />Programs
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: Private Credit Program -->
            <div class="group">
                <div class="mb-6 bg-[#0B231E] rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                    <!-- Mock Interface -->
                    <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3 border-b pb-2">
                            <div class="h-2 w-2 rounded-full bg-primary-500"></div>
                            <span class="text-[10px] font-mono text-gray-500">Private Credit Opportunity</span>
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center gap-2 text-xs text-primary-700">
                                <Check size={12} /> <span class="text-gray-600">Capital Preservation</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Steady Income Generation</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">High-Quality Credit Assets</span>
                            </div>
                            <div class="flex items-center gap-2 text-xs pl-4">
                                <span class="h-1 w-1 rounded-full bg-gray-300"></span> <span class="text-gray-400">Attractive Risk-Adjusted Returns</span>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Private Credit Program</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Focus on capital preservation and steady income generation through access to high-quality credit assets. Designed for investors seeking attractive risk-adjusted returns with lower volatility.
                </p>
            </div>

            <!-- Card 2: Private Equity Program -->
            <div class="group">
                <div class="mb-6 bg-[#0B231E] rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="text-[10px] text-gray-500 mb-2">Co-Investment Opportunities</div>
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-800 rounded flex items-center justify-center text-white text-[8px]">PE</div>
                            <span class="text-[10px] text-gray-400">Curated by experts</span>
                        </div>
                        <div class="space-y-2 border-t pt-2">
                            <div class="grid grid-cols-3 gap-2 text-[8px] text-gray-400 font-medium">
                                <div>Sector</div>
                                <div class="col-span-2 text-right">Target Return</div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> Technology</div>
                                <div class="col-span-2 h-1.5 bg-primary-100 rounded"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> Healthcare</div>
                                <div class="col-span-2 h-1.5 bg-primary-100 rounded w-2/3 ml-auto"></div>
                            </div>
                            <div class="grid grid-cols-3 gap-2 text-[9px] items-center">
                                <div class="flex items-center gap-1"><div class="h-2 w-2 bg-gray-200 rounded-sm"></div> Consumer</div>
                                <div class="col-span-2 h-1.5 bg-primary-100 rounded w-1/2 ml-auto"></div>
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Private Equity Program</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Exposure to high-growth private companies through direct investments and co-investments with top-tier sponsors. Significant capital appreciation potential over the long term.
                </p>
            </div>

            <!-- Card 3: Flagship PE Funds Program -->
            <div class="group">
                <div class="mb-6 bg-[#0B231E] rounded-lg p-6 aspect-[4/3] relative overflow-hidden flex flex-col">
                     <!-- Mock Interface -->
                     <div class="bg-white rounded-lg p-4 shadow-lg w-full max-w-[90%] mx-auto mt-auto mb-4 transform translate-y-2 transition-transform group-hover:translate-y-0">
                        <div class="flex items-center gap-2 mb-3">
                            <div class="h-4 w-4 bg-primary-800 rounded flex items-center justify-center text-white text-[8px]">F</div>
                            <span class="text-[10px] text-gray-500">Premier Fund Selection</span>
                        </div>
                        <div class="text-[9px] text-gray-600 mb-3 leading-relaxed">
                            Access to world-renowned sponsors with proven track records of success and diversified portfolios.
                        </div>
                        <div class="space-y-2">
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-primary-600 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Global Buyout Fund</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                            <div class="flex items-center justify-between p-1.5 bg-gray-50 rounded border border-gray-100">
                                <div class="flex items-center gap-2">
                                    <div class="h-4 w-4 bg-primary-700 rounded-sm"></div>
                                    <span class="text-[9px] font-medium">Growth Equity Fund</span>
                                </div>
                                <ArrowRight size={10} class="text-gray-400" />
                            </div>
                        </div>
                    </div>
                </div>
                <h3 class="text-xl font-serif text-gray-900 mb-3">Flagship PE Funds Program</h3>
                <p class="text-sm text-gray-500 leading-relaxed">
                    Selection of premier private equity funds managed by world-renowned sponsors. Diversified portfolios providing both growth and income with proven track records of success.
                </p>
            </div>
        </div>
    </div>
</section>
