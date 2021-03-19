<script>
  import TeamCard from "./TeamCard.svelte";
</script>

<!-- This example requires Tailwind CSS v2.0+ -->
<div class="bg-gray-900">
  <div class="mx-auto py-12 px-4 max-w-7xl sm:px-6 lg:px-8 lg:py-24">
    <div class="space-y-12">
      <div class="space-y-5 sm:space-y-4 md:max-w-xl lg:max-w-3xl xl:max-w-none">
        <h2 class="text-3xl font-extrabold text-white tracking-tight sm:text-4xl">Meet our team</h2>
        <p class="text-xl text-gray-300">Learn more about people behind the project.</p>
      </div>
      <ul class="space-y-4 sm:grid sm:grid-cols-2 sm:gap-6 sm:space-y-0 lg:grid-cols-3 lg:gap-8">
        <li class="py-10 px-6 bg-gray-800 text-center rounded-lg xl:px-10 xl:text-left">
          <TeamCard
            name="Vasco Sousa"
            avatar="./vasco.jpg"
            role="Developer"
            githubLink="https://github.com/mynameisvasco"
          />
        </li>
        <li class="py-10 px-6 bg-gray-800 text-center rounded-lg xl:px-10 xl:text-left">
          <TeamCard
            name="Francisco Monteiro"
            avatar="./francisco.jpg"
            role="Developer"
            githubLink="https://github.com/francisquinho85"
          />
        </li>
        <li class="py-10 px-6 bg-gray-800 text-center rounded-lg xl:px-10 xl:text-left">
          <TeamCard
            name="Daniel Andrade"
            avatar="./daniel.jpg"
            role="Developer"
            githubLink="https://github.com/mynameisvasco"
          />
        </li>
        <li class="py-10 px-6 bg-gray-800 text-center rounded-lg xl:px-10 xl:text-left">
          <TeamCard
            name="Roberto Graça"
            avatar="./roberto.jpg"
            role="Developer"
            githubLink="https://github.com/mynameisvasco"
          />
        </li>
        <li class="py-10 px-6 bg-gray-800 text-center rounded-lg xl:px-10 xl:text-left">
          <TeamCard
            name="Eduardo Almeida"
            avatar="./eduardo.jpg"
            role="Developer"
            githubLink="https://github.com/mynameisvasco"
          />
        </li>
        <li class="py-10 px-6 bg-gray-800 text-center rounded-lg xl:px-10 xl:text-left">
          <TeamCard
            name="Paulo Bartolomeu"
            avatar="https://upload.wikimedia.org/wikipedia/commons/7/7c/Profile_avatar_placeholder_large.png"
            role="Coordinator"
          />
        </li>
      </ul>
    </div>
  </div>
</div>
