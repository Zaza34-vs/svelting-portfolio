<script lang="ts">
    import Corpus from "./component/svelte/corpus.svelte";
    import Text from "./component/svelte/text.svelte";
    import Stack from "./component/svelte/stack.svelte";
    import Carrousel from "./component/svelte/carrousel.svelte";
</script>

<section>
    <Corpus />
</section>

<br>

<section class="secondSection">
    <h2>My Stack</h2>
    <Carrousel />
</section>

<style type="scss">
    @use '../sass/section.scss';
</style>