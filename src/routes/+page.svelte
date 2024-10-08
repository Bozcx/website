<script>
	import FirstSection from '$lib/components/FirstSection.svelte';
	import '$lib/index.css';
	import AboutSection from '$lib/components/AboutSection.svelte';
	import NavBar from '$lib/components/NavBar.svelte';
</script>

<section class="container">
	<NavBar/>
	<FirstSection/>
	<AboutSection/>
</section>

<style>
	.container {
      background-image: url("/img/gridbackground.png");
      background-size: cover;
	}
</style>