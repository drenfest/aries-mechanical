<script>
	import Nav from '../components/Nav.svelte';
	import MobileNav from '../components/MobileNav.svelte';
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
	export let segment;
	import Divider from '../components/Divider.svelte';
</script>


<style>

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
<Divider>
See Our Reviews
</Divider>
<section class="nn-section container">
	REPLACE-PHP-CODE-HERE
</section>
<Footer></Footer>
