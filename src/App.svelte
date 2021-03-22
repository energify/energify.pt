<script lang="ts">
  import { Router, Route } from "svelte-navigator";
  import Navbar from "./components/Navbar.svelte";
  import Deliverables from "./routes/deliverables/Deliverables.svelte";
  import Home from "./routes/home/Home.svelte";
</script>

<Router>
  <Navbar />
  <div>
    <Route path="/" component={Home} />
    <Route path="/deliverables" component={Deliverables} />
  </div>
</Router>

<style global>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
