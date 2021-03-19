<script>
  import FeaturesCard from "./FeaturesCard.svelte";
</script>

<div class="relative bg-gray-100 py-16 sm:py-24 lg:py-32">
  <div class="mx-auto max-w-md px-4 text-center sm:max-w-3xl sm:px-6 lg:px-8 lg:max-w-7xl">
    <h2 class="text-base font-semibold tracking-wider text-green-600 uppercase">Trade faster</h2>
    <p class="mt-2 text-3xl font-extrabold text-gray-900 tracking-tight sm:text-4xl">
      Everything you need to trade your energy
    </p>
    <p class="mt-5 max-w-prose mx-auto text-xl text-gray-500">
      Meet the feature that will empower your hability to buy and sell green energy.
    </p>
    <div class="mt-12">
      <div class="grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3">
        <FeaturesCard
          title="Decentralized"
          description="Due to distributed ledger technology, we can provide a decentralized way to process trade's payments."
        />
        <FeaturesCard
          title="Transparent"
          description="The system prevents tracking using a set of state of the art mechanisms. All information is private."
        />
        <FeaturesCard
          title="Law compliant"
          description="All features offered by our system, follow latest regulations from European Union about community green energy trading."
        />
      </div>
    </div>
  </div>
</div>
