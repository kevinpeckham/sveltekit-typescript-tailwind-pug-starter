<script lang="ts">
	// sveltekit error page documentation here:
	// https://kit.svelte.dev/docs/routing#error

	// import from svelte
	import { page } from "$app/stores";
</script>

<template lang="pug">
	.grid.h-screen.w-screen.grid-cols-1.place-content-center.place-items-center.bg-primary.text-36.text-white
		div { $page.status }: { $page.error.message }
</template>
