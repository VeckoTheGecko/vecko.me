<script>
	import "../app.css"
</script>

<div class="app flex flex-col min-h-screen">
	<header class="px-20 py-4 flex flex-row items-end">
		<a href="/" class="no-underline text-2xl text-vecko font-extrabold"> Vecko
		</a>
		<nav>
			<!-- <a href="/#" class="no-underline flex px-6">What is a Vecko?</a> -->
		</nav>
	</header>
	<div class="w-full h-0.5 bg-vecko"></div>
	<main class="flex-grow p-16">
		<slot />
	</main>

	<footer class="text-center text-xs py-4 opacity-20">
		<slot name="extra-footer"/>
		<p>© Nick Hodgskin. Fueled by falafel. Built using <a href="https://kit.svelte.dev/">SvelteKit</a> and <a href="https://tailwindcss.com/">Tailwind</a>.</p>
	</footer>
</div>
