<script lang="ts">
  import { users, cloud, cash } from "@martinse/svelte-heroicons/dist/solid/";

  import MoreFeaturesItem from "./MoreFeaturesItem.svelte";
</script>

<div class="py-16 bg-gray-50 overflow-hidden lg:py-24">
  <div class="relative max-w-xl mx-auto px-4 sm:px-6 lg:px-8 lg:max-w-7xl">
    <svg
      class="hidden lg:block absolute right-full transform translate-x-1/2 translate-y-12"
      width="404"
      height="784"
      fill="none"
      viewBox="0 0 404 784"
      aria-hidden="true"
    >
      <defs>
        <pattern
          id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d"
          x="0"
          y="0"
          width="20"
          height="20"
          patternUnits="userSpaceOnUse"
        >
          <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
        </pattern>
      </defs>
      <rect width="404" height="784" fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)" />
    </svg>

    <div class="relative">
      <div class="lg:grid lg:grid-flow-row-dense lg:grid-cols-2 lg:gap-8 lg:items-center">
        <div class="mt-10 relative lg:mt-0 lg:col-start-1">
          <svg
            class="absolute left-1/2 transform -translate-x-1/2 translate-y-16 lg:hidden"
            width="784"
            height="404"
            fill="none"
            viewBox="0 0 784 404"
            aria-hidden="true"
          >
            <defs>
              <pattern
                id="e80155a9-dfde-425a-b5ea-1f6fadd20131"
                x="0"
                y="0"
                width="20"
                height="20"
                patternUnits="userSpaceOnUse"
              >
                <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
              </pattern>
            </defs>
            <rect width="784" height="404" fill="url(#e80155a9-dfde-425a-b5ea-1f6fadd20131)" />
          </svg>
          <img
            class="relative rounded-lg hidden lg:flex"
            src="https://images.unsplash.com/photo-1498033435947-19325ae3d27f?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=500&h=700&q=80"
            alt=""
          />
        </div>
        <div class="lg:col-start-2">
          <h3 class="text-2xl font-extrabold text-gray-900 tracking-tight sm:text-3xl">
            Renewable energy communities
          </h3>
          <p class="mt-3 text-lg text-gray-500">
            Renewable energy communities is made of groups of citizens, social entrepreneurs, public
            authorities and community organisations directly involved in the energy transition by
            investing in, producing, selling and distributing renewable energy.
          </p>

          <dl class="mt-24 space-y-10">
            <MoreFeaturesItem
              title="Environmental Returns"
              description="All the energy used inside the community is 100% renewable, that leads to
                      environmental gains in long and short term."
              icon={cloud}
            />
            <MoreFeaturesItem
              title="Social Returns"
              description="The collective efforts needed to run the community are going to improve 
                    the social environment and make people feel connected."
              icon={users}
            />
            <MoreFeaturesItem
              title="Economic Returns"
              description="The profits of energy producing and the savings of energy consumption will
                      boost the overall income of families within the community."
              icon={cash}
            />
          </dl>
        </div>
      </div>
    </div>
  </div>
</div>
