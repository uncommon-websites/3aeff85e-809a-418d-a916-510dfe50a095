<script>
    import { Lock, Shield, Eye, FileCheck } from 'lucide-svelte';
</script>

<section class="bg-[#111111] text-white py-24">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-16">
            <!-- Left Content -->
            <div class="flex flex-col justify-center">
                <div class="flex items-center gap-2 mb-8">
                    <Shield size={16} class="text-white" />
                    <span class="text-xs font-mono uppercase tracking-widest text-gray-400">Regulation</span>
                </div>

                <h2 class="text-4xl md:text-5xl font-serif mb-2">Globally Regulated</h2>
                <h2 class="text-4xl md:text-5xl font-serif mb-12">Fully Compliant</h2>

                <div class="space-y-4 mb-12">
                    <div class="flex items-center gap-3">
                        <Shield size={16} class="text-gray-400" />
                        <span class="text-sm font-medium">Four regulatory licenses globally</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <FileCheck size={16} class="text-gray-400" />
                        <span class="text-sm font-medium">PRI signatory for responsible investing</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <Lock size={16} class="text-gray-400" />
                        <span class="text-sm font-medium">Secure digital infrastructure</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <Eye size={16} class="text-gray-400" />
                        <span class="text-sm font-medium">Complete transparency & reporting</span>
                    </div>
                </div>

                <a href="#regulation" class="inline-flex items-center text-sm font-medium text-white hover:text-gray-300 transition-colors">
                    Learn about our licenses <span class="ml-2">↗</span>
                </a>
            </div>

            <!-- Right Content: Regulatory Licenses Grid -->
            <div class="grid grid-cols-2 border-t border-l border-gray-800">
                <!-- FINMA -->
                <div class="aspect-square border-r border-b border-gray-800 flex flex-col items-center justify-center p-8 relative group">
                    <div class="h-24 w-24 rounded-full border-2 border-gray-600 flex items-center justify-center mb-4 opacity-70 group-hover:opacity-100 transition-opacity">
                        <div class="text-center">
                            <div class="text-lg font-bold">FINMA</div>
                            <div class="text-[10px] text-gray-400 mt-1">Switzerland</div>
                        </div>
                    </div>
                    <span class="absolute bottom-4 left-4 text-[10px] text-gray-500 font-mono">Swiss Regulator</span>
                </div>

                <!-- SEC -->
                <div class="aspect-square border-r border-b border-gray-800 flex flex-col items-center justify-center p-8 relative group">
                    <div class="h-24 w-24 rounded-full border-2 border-gray-600 flex items-center justify-center mb-4 opacity-70 group-hover:opacity-100 transition-opacity">
                        <div class="text-center">
                            <div class="text-lg font-bold">SEC</div>
                            <div class="text-[10px] text-gray-400 mt-1">United States</div>
                        </div>
                    </div>
                    <span class="absolute bottom-4 left-4 text-[10px] text-gray-500 font-mono">US Regulator</span>
                </div>

                <!-- SFC -->
                <div class="aspect-square border-r border-b border-gray-800 flex flex-col items-center justify-center p-8 relative group">
                    <div class="h-24 w-24 rounded-full border-2 border-gray-600 flex items-center justify-center mb-4 opacity-70 group-hover:opacity-100 transition-opacity">
                         <div class="text-center">
                            <div class="text-lg font-bold">SFC</div>
                            <div class="text-[10px] text-gray-400 mt-1">Hong Kong</div>
                        </div>
                    </div>
                    <span class="absolute bottom-4 left-4 text-[10px] text-gray-500 font-mono">HK Regulator</span>
                </div>

                <!-- CIMA -->
                <div class="aspect-square border-r border-b border-gray-800 flex flex-col items-center justify-center p-8 relative group">
                    <div class="h-24 w-24 rounded-full border-2 border-gray-600 flex items-center justify-center mb-4 opacity-70 group-hover:opacity-100 transition-opacity">
                        <div class="text-center">
                            <div class="text-lg font-bold">CIMA</div>
                            <div class="text-[10px] text-gray-400 mt-1">Cayman Islands</div>
                        </div>
                    </div>
                    <span class="absolute bottom-4 left-4 text-[10px] text-gray-500 font-mono">Cayman Regulator</span>
                </div>
            </div>
        </div>
    </div>
</section>
