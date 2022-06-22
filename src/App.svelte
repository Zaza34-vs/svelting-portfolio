<script lang="ts">
	import Header from './header.svelte';
	import Section from './section.svelte';
	import Footer from './footer.svelte';

	export let name: string;
	name = "Friend";
</script>

<body>
	<header>
		<Header/>
	</header>
	
	<section>
		<Section/>
	</section>
	
	<footer>
		<Footer/>
	</footer>
</body>

<style type="scss">
	@use '../sass/main.scss';
</style>