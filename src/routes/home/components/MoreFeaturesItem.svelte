<script lang="ts">
  import Heroicon from "@martinse/svelte-heroicons";

  export let title: string;
  export let description: string;
  export let icon: any;
</script>

<div class="relative">
  <dt>
    <div
      class="absolute flex items-center justify-center h-12 w-12 rounded-md
         bg-gray-900 text-green-400"
    >
      <Heroicon class="h-6 w-6" {icon} />
    </div>
    <p class="ml-16 text-lg leading-6 font-medium text-gray-900">{title}</p>
  </dt>
  <dd class="mt-2 ml-16 text-base text-gray-500">
    {description}
  </dd>
</div>
