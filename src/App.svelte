<script lang="ts">
  import { Router, Link, Route } from "svelte-navigator";
  import Home from "./routes/home/Home.svelte";
</script>

<Router>
  <nav />

  <div>
    <Route path="/" component={Home} />
  </div>
</Router>

<style global>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
