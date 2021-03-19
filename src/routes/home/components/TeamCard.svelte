<script lang="ts">
  export let name: string;
  export let role: string;
  export let description: string;
  export let avatar: string;
</script>

<div class="space-y-4 sm:grid sm:grid-cols-3 sm:gap-6 sm:space-y-0 lg:gap-8 py-8">
  <div class="h-0 aspect-w-3 aspect-h-2 sm:aspect-w-3 sm:aspect-h-4">
    <img class="object-cover shadow-lg rounded-lg" src={avatar} alt="" />
  </div>
  <div class="sm:col-span-2">
    <div class="space-y-4">
      <div class="text-lg leading-6 font-medium space-y-1">
        <h3>{name}</h3>
        <p class="text-green-600">{role}</p>
      </div>
      <div class="text-lg">
        <p class="text-gray-500">
          {description}
        </p>
      </div>
    </div>
  </div>
</div>
