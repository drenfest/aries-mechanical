<script>
    import Hero from '../../components/Hero.svelte';
    import CouponSidebar from '../../components/CouponSidebar.svelte';
</script>
<style>
    .address{
        padding:2rem;
    }
</style>
<Hero
        heroImage="/assets/images/heros/hmhero1.jpg"
        heroTitle="Contact Aries Mechanical"
        heroBigText="Affordable & Quality HVAC Services For Over 30 Years"
        heroText=" Your Hvac | A/C | Furnace Installation & Repair Company">
    <p>Our customers are treated as if they are part of our family. We respect our customers and listen to their needs. We provide our customers with honesty and reliability that they deserve. Aries Mechanical, Inc. is known for our quality craftsmanship at competitive prices.</p>
    <a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<div class="container">
    <div class="row">
        <section class="content col-xs-12 col-sm-8">
            <slot></slot>
        </section>
        <aside class="content col-xs-12 col-sm-4">
            <div class="address">
                <h2>Contact Info</h2>
                <strong>Address: </strong>
                <address>
                    101 East Taylor Street
                    Newark, IL 60541
                </address>
                <strong>Phone: </strong><a href="tel:+1815-695-5828">815.695.5828</a><br>
                <strong>Email: </strong><a href="mailto:steve@aries-mechanical.com">steve@aries-mechanical.com</a>
            </div>
            <CouponSidebar/>
        </aside>
    </div>
    <section class="nn-section container">
        REPLACE-PHP-CODE-HERE
    </section>
</div>
