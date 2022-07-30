<script lang="ts">
	import { Router, Route } from "svelte-routing";
	import Home from "./pages/Home.svelte";
import NotFound from "./pages/NotFound.svelte";
</script>

<Router>
	<Route path="/" component={Home} />
	<Route path="*" component={NotFound}/>
</Router>
