<script lang="ts">
  import Heroicon from "@martinse/svelte-heroicons";

  export let title: string;
  export let description: string;
  export let icon: any;
</script>

<div class="pt-6">
  <div class="flow-root bg-white rounded-lg px-6 pb-8 shadow-sm">
    <div class="-mt-6">
      <div>
        <span
          class="inline-flex items-center justify-center p-3 bg-gray-800 rounded-md shadow-lg
          text-green-400"
        >
          <Heroicon class="h-6 w-6" {icon} />
        </span>
      </div>
      <h3 class="mt-8 text-lg font-medium text-gray-900 tracking-tight">{title}</h3>
      <p class="mt-5 text-base text-gray-500">
        {description}
      </p>
    </div>
  </div>
</div>
