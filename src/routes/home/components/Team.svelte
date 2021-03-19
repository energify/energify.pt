<script>
  import TeamCard from "./TeamCard.svelte";
</script>

<div class="bg-white">
  <div class="mx-auto py-12 px-4 max-w-7xl sm:px-6 lg:px-8 lg:py-24">
    <div class="space-y-12">
      <h2 class="text-3xl font-extrabold tracking-tight sm:text-4xl">Meet our leadership</h2>
      <ul
        class="space-y-12 lg:grid lg:grid-cols-2 lg:items-start lg:gap-x-8 lg:gap-y-12 lg:space-y-0"
      >
        <li>
          <TeamCard
            name="Vasco Sousa"
            avatar="./vasco.jpg"
            role="Developer"
            description="A passionate full stack developer, who is loooking to build smart solutions to hard daily problems."
          />
        </li>
        <li>
          <TeamCard
            name="Francisco Monteiro"
            avatar="francisco.jpg"
            role="Developer"
            description="A young and bright star of engineering, who solves real life problems through technological approaches."
          />
        </li>
        <li>
          <TeamCard
            name="Daniel Andrade"
            avatar="daniel.jpg"
            role="Developer"
            description="An enthusiast student of engineering whose purpose is to make the world a better place through research and development."
          />
        </li>
        <li>
          <TeamCard
            name="Roberto Graça"
            avatar="roberto.jpg"
            role="Developer"
            description="A dedicated student of engineering focused on doing things one at a time."
          />
        </li>
        <li>
          <TeamCard
            name="Eduardo Almeida"
            avatar="eduardo.jpg"
            role="Developer"
            description="A young and bright star of engineering, who solves real life problems through technological approaches."
          />
        </li>
        <li>
          <TeamCard
            name="Paulo Bartolomeu"
            avatar="https://jsl-online.com/wp-content/uploads/2017/01/placeholder-user.png"
            role="Coordinator"
            description="Researcher with Ph.D. at Universidade de Aveiro."
          />
        </li>
      </ul>
    </div>
  </div>
</div>
