<script>
	import "../output.css"
</script>

<div class="app flex flex-col min-h-screen">
	<main class="flex-grow">
		<slot />
	</main>

	<footer class="text-center py-4">
		<p>Built using <a href="https://kit.svelte.dev/">SvelteKit</a> and <a href="https://tailwindcss.com/">Tailwind</a>.</p>
	</footer>
</div>
