<script>
	import Card from '../components/Card.svelte';
	import Footer from '../components/Footer/Footer.svelte';
	import Hero from '../components/Hero/Hero.svelte';
</script>

<main class="container mx-auto flex w-full justify-center py-10 px-10 bg-base-100">
	<div class="">
		<Hero />
		<div class="grid sm:grid-cols-3 grid-col-1 gap-10">
			<Card />
			<Card />
			<Card />
			<Card />
			<Card />
		</div>
	</div>
</main>

<Footer />

<style>
</style>
