<script lang="ts">
	import img from "$lib/images/pfp.png";
</script>

<header class="w-full p-4 border-b">
	<h1 class="inline text-3xl">Nicole's Cabin</h1>
	<div id="pfp" style="background-image: url({img})" class="ml-2 hover:ml-4 inline-block align-middle w-16 aspect-square rounded-lg">
</header>

<style>
	#pfp {
		background-position: 50%;
		background-size: 120%;
		transition: 0.3s;
	}
	#pfp:hover {
		background-size: 100%;
		transform: scale(1.2);
	}
</style>