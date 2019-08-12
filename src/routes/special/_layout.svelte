<script>
    import Hero from '../../components/Hero.svelte';
    import CouponSidebar from '../../components/CouponSidebar.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/hmhero1.jpg"
        heroTitle="Specials"
        heroBigText="Affordable & Quality HVAC Services For Over 30 Years"
        heroText=" Your Hvac | A/C | Furnace Installation & Repair Company">
    <p>Our customers are treated as if they are part of our family. We respect our customers and listen to their needs. We provide our customers with honesty and reliability that they deserve. Aries Mechanical, Inc. is known for our quality craftsmanship at competitive prices.</p>
    <a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<div class="container">
        <section class="content">
            <slot></slot>
        </section>
</div>
