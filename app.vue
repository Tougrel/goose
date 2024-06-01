<script setup lang="ts">
useHead({
	title: "ΒΡΩΜΙΑΡΑ ΧΗΝΑ",
	link: [
		{
			rel: "icon",
			href: "/favicon.svg",
		},
		{
			rel: "mask-icon",
			href: "/favicon.svg",
			color: "#FFF",
		},
	],
});
</script>

<template>
	<h1 class="text-4xl font-bold text-red-400">ΠΡΟΣΟΧΗ</h1>
	<p class="text-xl font-medium text-blue-400">Η ΠΑΠΙΑ ΕΙΝΑΙ ΒΡΩΜΙΑΡΑ</p>
	<NuxtImg src="assets/goose.jpg" width="1024" class="rounded-lg" />
</template>

<style>
html {
	@apply flex flex-col items-center text-center justify-center h-screen bg-neutral-900;
}
</style>
