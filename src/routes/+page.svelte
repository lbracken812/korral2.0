<script>
	import About from '../components/landing/About.svelte';
	import Hero from '../components/landing/Hero.svelte';
	import Projects from '../components/landing/Projects.svelte';
	import Tech from '../components/landing/Tech.svelte';
</script>

<svelte:head>
	<title>Logan Bracken</title>
	<meta name="description" content="Crafting powerful websites and web applications" />
</svelte:head>

<section class="flex flex-col gap-24">
	<Hero />
	<About />
	<Projects />
	<Tech />
</section>
