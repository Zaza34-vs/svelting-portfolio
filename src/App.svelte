<script lang="ts">
	export let name: string;
	name = "Friend";
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style type="scss">
	@use '../sass/main.scss';
</style>