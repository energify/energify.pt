<script lang="ts">
  export let title: string;
</script>

<div class="col-span-6 lg:col-span-3">
  <dt class="text-lg leading-6 font-medium text-gray-900">{title}</dt>
  <dd class="mt-2 text-base text-gray-500 flex flex-col">
    <slot />
  </dd>
</div>
