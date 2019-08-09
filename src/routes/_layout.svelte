<script>
	import Nav from '../components/Nav.svelte';
	import MobileNav from '../components/MobileNav.svelte';
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
	export let segment;
</script>


<style>
</style>
<MobileNav {segment}/>
<Header></Header>
<Nav {segment}/>
<main>
	<slot></slot>
</main>
<Footer></Footer>
