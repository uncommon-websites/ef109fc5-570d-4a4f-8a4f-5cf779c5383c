<script lang="ts">
  import SectionWrapper from './SectionWrapper.svelte';
</script>

<SectionWrapper withBorderBottom={true} className="py-12">
  <div class="px-4 md:px-12 flex flex-col md:flex-row items-center justify-center gap-8">
    <!-- Market Info -->
    <div class="text-center max-w-3xl">
      <div class="text-gray-400 text-sm font-light">
        Built for independent financial advisors at mid-market RIAs
      </div>
      <div class="text-gray-500 text-xs mt-2">
        Targeting 12,300 firms in a $2.5B market opportunity
      </div>
    </div>
  </div>
</SectionWrapper>
