<script lang="ts">
	import Header from './Header.svelte';
	import '../app.css';
	
	let { children } = $props();
</script>

<div class="app">
	<Header />

	<main>
		{@render children()}
	</main>
</div>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.slate.800);
		color: theme(colors.slate.100);
		font-family: 'Inter', 'system-ui', 'sans-serif';
	}
</style>
