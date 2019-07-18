<script>
	import Header from './Header.svelte';
	import Auto from './Auto.svelte';
	import Freebet from './Freebet.svelte';
	import Gadjet from './Gadjet.svelte';
	import Pari from './Pari.svelte';
	import Documents from './Documents.svelte';
	import Banner from './Banner.svelte';
	import Footer from './Footer.svelte';
</script>

<style>
	.wrapper{
		margin: 0 auto;
		background-color: var(--vlGreen);
		color: #fff
	}

</style>

<Header/>
<main class="wrapper">
	<Auto/>
	<Freebet/>
	<Gadjet/>
	<Pari/>
	<Documents/>
	<Banner/>
</main>	
<Footer/>