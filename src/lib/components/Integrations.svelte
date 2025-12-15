<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-24">
  <div class="px-4 md:px-12 max-w-4xl mx-auto text-center mb-16">
    <div class="text-xs font-mono uppercase tracking-widest text-gray-500 mb-4">
      Integrations
    </div>
    <h2 class="font-serif text-4xl text-gray-900 mb-6">
      Seamlessly connect your ecosystem
    </h2>
    <p class="text-gray-500 leading-relaxed max-w-2xl mx-auto">
      Deep integrations with leading custodians and CRM systems. Neptune unifies your technology stack into a single, intelligent platform managing real client assets.
    </p>
  </div>

  <div class="px-4 md:px-12 relative">
    <!-- Connecting Line -->
    <div class="absolute top-1/2 left-0 w-full h-px bg-gray-200 -translate-y-1/2 hidden md:block"></div>

    <!-- Logos Row -->
    <div class="flex flex-wrap md:flex-nowrap items-center justify-center md:justify-between gap-8 relative z-10">
      
      <!-- Logo 1 - Schwab -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-blue-600">Schwab</div>
      </div>

       <!-- Logo 2 - Interactive Brokers -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-700">IBKR</div>
      </div>

       <!-- Center Logo (Neptune) -->
      <div class="w-24 h-24 bg-[var(--color-primary-blue)] rounded-full shadow-lg border-4 border-white flex items-center justify-center p-2 relative">
        <div class="text-white font-serif font-bold text-xs tracking-wide">NEPTUNE</div>
        <!-- Orbit ring visual -->
        <div class="absolute inset-0 rounded-full border border-primary-700 scale-110 opacity-50"></div>
      </div>

       <!-- Logo 3 - CRM -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-primary-600">CRM</div>
      </div>

       <!-- Logo 4 - Custodian -->
      <div class="w-16 h-16 bg-white rounded-full shadow-sm border border-gray-100 flex items-center justify-center p-3">
        <div class="text-[10px] font-bold text-gray-600">DATA</div>
      </div>

    </div>
  </div>
</SectionWrapper>
