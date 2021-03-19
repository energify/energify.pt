<script lang="ts">
  export let name: string;
  export let role: string;
  export let githubLink: string;
  export let avatar: string;
</script>

<div class="space-y-6 xl:space-y-10">
  <img class="mx-auto h-40 w-40 rounded-full xl:w-56 xl:h-56" src={avatar} alt="" />
  <div class="space-y-2 xl:flex xl:items-center xl:justify-between">
    <div class="font-medium text-lg leading-6 space-y-1">
      <h3 class="text-white">{name}</h3>
      <p class="text-green-400">{role}</p>
    </div>

    <ul class="flex justify-center space-x-5">
      {#if githubLink}
        <li>
          <a target="_blank" href={githubLink} class="text-gray-400 hover:text-gray-300">
            <span class="sr-only">Github</span>
            <i class="fab fa-github" />
          </a>
        </li>
      {/if}
    </ul>
  </div>
</div>
