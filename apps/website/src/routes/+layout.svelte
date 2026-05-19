<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>LeftyDevKit — Building tech for a better world</title>
	<meta name="description" content="Open-source progressive civic-tech tools. Free for candidates and organizers who align with our values." />
	<meta name="viewport" content="width=device-width, initial-scale=1" />
</svelte:head>

<nav>
	<div class="container">
		<a href="/" class="logo">Lefty<span>DevKit</span></a>
		<div class="nav-links">
			<a href="#projects">Projects</a>
			<a href="#mission">Mission</a>
			<a href="#stream">Stream</a>
			<a href="https://github.com/techydad05/leftydevkit" target="_blank">GitHub</a>
		</div>
	</div>
</nav>

{@render children()}

<footer>
	<div class="container">
		<p>LeftyDevKit — <a href="https://github.com/techydad05/leftydevkit">open source</a> &bull; MIT license &bull; Free for progressive candidates</p>
		<p style="margin-top: 8px; font-size: 0.8rem;">Built in public, one stream at a time.</p>
	</div>
</footer>
