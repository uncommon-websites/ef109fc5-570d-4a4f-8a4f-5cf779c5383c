<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
  import SolutionBlock from './SolutionBlock.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="">
  <div class="px-4 md:px-12">
    <div class="py-16 text-center">
      <h2 class="font-serif text-4xl text-gray-900">AI agents that run investment firms</h2>
    </div>

    <!-- Block 1 -->
    <SolutionBlock
      label="AI Portfolio Management"
      title="Institutional-grade investment automation"
      description="Proprietary trading engine with automated rebalancing, tax-loss harvesting, and real-time market adaptation. Separately Managed Accounts (SMAs), direct indexing, and highly customized portfolio construction—all managed by AI proven with $52M in live client assets."
    >
      <!-- Visual for Block 1: Portfolio Management -->
      <div class="relative w-full h-full flex items-center justify-center">
        <!-- Central AI Hub -->
        <div class="w-16 h-16 bg-white shadow-lg rounded-lg flex items-center justify-center z-10 border border-gray-100">
           <div class="w-8 h-8 bg-[var(--color-primary-blue)] rounded-sm"></div>
        </div>
        
        <!-- Connected Portfolio Elements -->
        <div class="absolute top-1/4 left-1/4 bg-white p-3 shadow rounded border border-gray-100 animate-pulse">
            <div class="w-8 h-10 bg-primary-100 rounded flex items-center justify-center text-[10px] font-bold text-primary-700">SMA</div>
            <div class="mt-1 text-[10px] text-center">Managed</div>
        </div>
        <div class="absolute top-1/4 right-1/4 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-primary-800 rounded flex items-center justify-center text-[10px] font-bold text-white">TAX</div>
            <div class="mt-1 text-[10px] text-center">Harvest</div>
        </div>
        <div class="absolute bottom-1/4 left-1/3 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-primary-500 rounded flex items-center justify-center text-[10px] font-bold text-white">IDX</div>
            <div class="mt-1 text-[10px] text-center">Direct</div>
        </div>
         <div class="absolute bottom-1/4 right-1/3 bg-white p-3 shadow rounded border border-gray-100">
            <div class="w-8 h-10 bg-gray-200 rounded flex items-center justify-center text-[10px] font-bold text-gray-600">BAL</div>
            <div class="mt-1 text-[10px] text-center">Rebalance</div>
        </div>
        
        <!-- Connecting Lines (Simplified) -->
        <svg class="absolute inset-0 w-full h-full pointer-events-none opacity-20" viewBox="0 0 400 300">
            <path d="M100 100 L200 150 M300 100 L200 150 M150 220 L200 150 M250 220 L200 150" stroke="currentColor" stroke-width="1" stroke-dasharray="4 4" />
        </svg>
      </div>
    </SolutionBlock>

    <!-- Block 2 -->
    <SolutionBlock
      label="Operational Automation"
      title="End-to-end workflow intelligence"
      description="Agentic AI handles client onboarding, KYC compliance, automated reporting, voice and email communications, and secure portal management. No-code workflow editor lets you customize every process. Scale your practice without adding headcount."
      reversed={true}
    >
      <!-- Visual for Block 2: Automation Card -->
      <div class="bg-white rounded-lg shadow-xl p-6 w-3/4 max-w-sm border border-gray-100">
        <div class="flex items-center space-x-3 mb-4">
            <div class="w-8 h-8 rounded-full bg-gray-300 overflow-hidden">
                <img src="https://i.pravatar.cc/100?img=5" alt="Avatar" class="w-full h-full object-cover" />
            </div>
            <div class="text-xs text-gray-500">Sarah Johnson • Client Onboarding</div>
        </div>
        <h4 class="font-serif text-xl mb-4">New Client Setup</h4>
        <div class="space-y-2 mb-6">
            <div class="h-2 bg-gray-100 rounded w-full"></div>
            <div class="h-2 bg-gray-100 rounded w-5/6"></div>
            <div class="h-2 bg-gray-100 rounded w-4/6"></div>
        </div>
        <button class="w-full bg-[var(--color-primary-blue)] text-white py-2 rounded text-sm font-medium flex items-center justify-center space-x-2">
            <span>Auto-Generate KYC Report</span>
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </button>
      </div>
    </SolutionBlock>

    <!-- Block 3 -->
    <SolutionBlock
      label="Compliance & Security"
      title="Fiduciary-first, enterprise-grade protection"
      description="SOC II Type I and HIPAA-ready infrastructure designed for registered investment advisors. Maintain fiduciary standard with client-first recommendations. Automated compliance processing, intelligent document handling, and exception-based human oversight ensure regulatory adherence."
    >
       <!-- Visual for Block 3: Compliance Report -->
       <div class="bg-white rounded shadow-lg p-8 w-2/3 max-w-xs border border-gray-100 relative">
          <div class="flex justify-between items-center mb-6 border-b pb-2">
              <div class="font-bold text-xs">Neptune Advisory</div>
              <div class="w-4 h-4 bg-[var(--color-primary-blue)] rounded-full"></div>
          </div>
          <div class="mb-4">
              <h5 class="font-bold text-sm">Compliance Report</h5>
              <div class="text-[10px] text-gray-400">SOC II Type I Ready • Fiduciary Standard</div>
          </div>
          <div class="space-y-2 text-[8px] text-gray-500 leading-relaxed">
              <p>All client accounts maintain fiduciary compliance with automated risk assessment and regulatory adherence monitoring.</p>
              <p>Portfolio recommendations align with stated investment objectives and risk tolerance profiles per SEC requirements.</p>
          </div>
       </div>
    </SolutionBlock>
  </div>
</SectionWrapper>
