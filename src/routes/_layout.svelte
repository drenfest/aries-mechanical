<script>
	import Nav from '../components/Nav.svelte';
	import MobileNav from '../components/MobileNav.svelte';
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
	import Divider from '../components/Divider.svelte';
	import WhyUs from '../components/WhyUs.svelte';
	export let segment;
</script>


<style>
.nn-section{
	padding:2rem;
}
</style>
<MobileNav {segment}/>
<Header></Header>
<Nav {segment}/>
{#if segment === undefined}
	<main>
		<slot></slot>
	</main>
	<WhyUs></WhyUs>
	<Divider>
		<h2>See Our Reviews</h2>
	</Divider>
	<section class="nn-section container">
		REPLACE-PHP-CODE-HERE
	</section>
	{:else}
		<main class="{segment} subpage">
			<slot></slot>
		</main>
{/if}
<Footer></Footer>
