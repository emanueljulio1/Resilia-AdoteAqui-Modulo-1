<script>
	import "smelte/src/tailwind.css" ;
	export let url = "";
	import { Router, Link, Route } from "svelte-routing";		
	import Header from "./components/Header.svelte";
	import Footer from "./components/Footer.svelte";
	import Home from './components/Home.svelte';
	import Sobre from './components/Sobre.svelte';
	import Contato from './components/Contato.svelte';
</script>

<main class='bg-background-500'>

	
	<Header />
	<section class='content'>
		<Router url="{url}">
			<Route path="contatos" component="{Contato}" />
			<Route path="sobre" component="{Sobre}" />
			<Route path="/"><Home /></Route>
		</Router>
	</section>
	<Footer />


</main>

<style>
	main{
		text-align: center;
		max-width: 640px;
		margin: 0 auto;
	}

	.content{
		min-height: calc(100vh - 60px - 60px);
	}
</style>
