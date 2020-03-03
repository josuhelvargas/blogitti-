
<script>
	import Home from './Home.svelte';
	import Login from './Login.svelte';
	import NavigationTop from './NavigationTop.svelte';
	import ITraining from './ITraining.svelte';
</script>



<main>
<NavigationTop></NavigationTop>
<br/>
<!-- <Login></Login> -->
<ITraining></ITraining>
</main>

<style>
	main {
		text-align: center;
		padding: 2em;
		max-width: 80px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
 