<script>
    import Hero from '../../components/Hero.svelte';
    import CouponSidebar from '../../components/CouponSidebar.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/achero2.jpg"
        heroTitle="Affordable & High Quality HVAC Services"
        heroBigText="Air Conditioner Repair"
        heroText=" Your Hvac | A/C | Furnace Installation & Repair Company For Over 30 Years">
    <p>We have your comfort level at the top of our list, never leaving you waiting, or leaving you without a resolution.</p>
    <a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<div class="container">
    <div class="row">
        <section class="content col-xs-12 col-sm-8">
            <slot></slot>
        </section>
        <aside class="content col-xs-12 col-sm-4">
            <CouponSidebar/>
        </aside>
    </div>
</div>
