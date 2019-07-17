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
	@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed&display=swap');
	.wrapper{
		margin: 0 auto;
		background-color: #006237;
		color: #fff;
		padding: 16px;
	}
	.container{
		width:1100px;
		margin: auto
	}

	.second div{
		border-radius: 6px;
		background-color: #006237;
	}

	.second h3{
		color: #d2d700;
	}

	.second span{
		color: #d2d700;
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