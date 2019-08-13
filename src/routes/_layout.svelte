<script>
	import Nav from '../components/Nav.svelte';
	import MobileNav from '../components/MobileNav.svelte';
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
	import Divider from '../components/Divider.svelte';
	import WhyUs from '../components/WhyUs.svelte';
	import Nn from '../components/Nn.svelte';
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
	{:else}
		<main class="{segment} subpage">
			<slot></slot>
		</main>

{/if}
<div class="container">
	<WhyUs></WhyUs>
</div>
<Divider>
	<h2>See Our Reviews</h2>
</Divider>
<Nn></Nn>
<Footer></Footer>
