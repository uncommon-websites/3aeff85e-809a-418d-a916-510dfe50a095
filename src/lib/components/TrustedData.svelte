<script>
    const partners = [
        { name: "Apollo Global Management", icon: "A", color: "bg-gray-900" },
        { name: "KKR", icon: "K", color: "bg-gray-800" },
        { name: "The Carlyle Group", icon: "C", color: "bg-gray-900" },
        { name: "Oaktree Capital", icon: "O", color: "bg-primary-800" },
        { name: "BlackRock", icon: "B", color: "bg-gray-900" },
        { name: "Goldman Sachs", icon: "G", color: "bg-blue-900" },
        { name: "Silver Lake", icon: "S", color: "bg-gray-700" },
        { name: "Partners Group", icon: "P", color: "bg-primary-700" },
        { name: "Neuberger Berman", icon: "N", color: "bg-blue-800" },
        { name: "North Castle Partners", icon: "N", color: "bg-gray-800" },
        { name: "Skyview Capital", icon: "S", color: "bg-primary-600" },
        { name: "AS Birch Grove", icon: "B", color: "bg-gray-700" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-2xl">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">World-Class Investment Partners</h2>
            <p class="text-sm text-gray-500 leading-relaxed">
                We partner with elite private equity sponsors and asset managers to bring institutional-grade investment opportunities to our platform. 20 years of relationship building enables access to deals typically reserved for large institutions.
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            {#each partners as partner}
                <div class="flex items-center gap-4 p-4 bg-gray-50 rounded-lg hover:bg-gray-100 transition-colors cursor-default">
                    <div class={`h-8 w-8 rounded flex items-center justify-center text-white text-xs font-bold ${partner.color}`}>
                        {partner.icon}
                    </div>
                    <span class="text-sm font-medium text-gray-900">{partner.name}</span>
                </div>
            {/each}
        </div>
    </div>
</section>
