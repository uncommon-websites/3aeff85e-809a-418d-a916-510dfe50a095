<script>
  // No imports needed as we use inline SVGs for specific styling control
</script>

<section class="relative flex flex-col items-center justify-start pt-20 pb-32 overflow-hidden">
  <!-- Content -->
  <div class="z-10 mx-auto max-w-4xl px-4 text-center mb-16">
    <h1 class="mb-6 text-5xl md:text-6xl lg:text-7xl font-serif text-gray-900 leading-tight">
      Institutional Private Markets,<br />Now Accessible
    </h1>
    <p class="mx-auto mb-10 max-w-2xl text-lg text-gray-600 leading-relaxed">
      Access curated private equity, private credit, and real estate investments from world-class sponsors with lower minimums and full digital transparency
    </p>
    
    <div class="flex justify-center">
        <div class="relative group">
            <!-- Decorative brackets/corners could be added here if needed, but simple button for now -->
            <button class="relative rounded-full bg-black px-8 py-3 text-base font-medium text-white hover:bg-gray-800 transition-all">
                Explore Opportunities
            </button>
            <!-- Decorative corners -->
            <div class="absolute -top-2 -left-2 h-4 w-4 border-t-2 border-l-2 border-black"></div>
            <div class="absolute -bottom-2 -right-2 h-4 w-4 border-b-2 border-r-2 border-black"></div>
        </div>
    </div>
  </div>

  <!-- Hero Image -->
  <div class="relative w-full max-w-7xl mx-auto px-4">
    <div class="relative aspect-[21/9] w-full overflow-hidden rounded-lg shadow-2xl">
      <img 
        src="/generated/image-professional-wealth-advisor-meeting-with-1765584016627-0.webp" 
        alt="Professional wealth advisor consulting with client" 
        class="h-full w-full object-cover"
      />
      
      <!-- Overlay Stats Card -->
      <div class="absolute inset-0 flex items-center justify-center bg-black/5">
        <div class="w-full max-w-xl rounded-xl bg-white p-6 shadow-xl animate-fade-in-up">
            <div class="grid grid-cols-3 gap-6">
              <div class="text-center border-r border-gray-200">
                <div class="text-3xl font-bold text-gray-900 mb-1">$2.2B+</div>
                <div class="text-xs text-gray-500 uppercase tracking-wide">Assets Under Management</div>
              </div>
              <div class="text-center border-r border-gray-200">
                <div class="text-3xl font-bold text-gray-900 mb-1">20+</div>
                <div class="text-xs text-gray-500 uppercase tracking-wide">Years Experience</div>
              </div>
              <div class="text-center">
                <div class="text-3xl font-bold text-gray-900 mb-1">4%</div>
                <div class="text-xs text-gray-500 uppercase tracking-wide">Deal Selection Rate</div>
              </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
    .animate-fade-in-up {
        animation: fadeInUp 0.8s ease-out forwards;
    }
    @keyframes fadeInUp {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }
</style>
