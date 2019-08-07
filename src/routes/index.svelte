<script>
	import Hero from '../components/Hero.svelte';
	import ServiceBtn from '../components/ServiceBtn.svelte';
	import Divider from '../components/Divider.svelte';
	import Coupon from '../components/Coupon.svelte';
	import TraneBanner from '../components/TraneBanner.svelte';
	import ServicesGrid from '../components/ServicesGrid.svelte';
</script>
<style>
	.about-section{
		padding:2rem;
	}
	.about-section > .container > h2{
		margin-bottom:1rem;
	}
	.service-btns-bg{
		background: rgb(113,29,29);
		background: linear-gradient(180deg, rgba(113,29,29,1) 0%, rgba(157,39,40,1) 50%, rgba(236,50,55,1) 100%);
	}
	.service-buttons{
		display:grid;
		grid-template-rows:1fr 1fr 1fr;
	}
	.coupon-section{
		background: #e6e6e6;
		padding:3rem 0;
	}
	.specials-button{
		margin-top:2rem;
	}
	.specials-button>a{
		background-color:var(--primary-color);
		border:none;
		border-radius:0;
	}
	.specials-button>a:hover{
		background-color:#711D1D;
	}
	@media screen and (min-width:768px){
		.service-btns-bg{
			background: rgb(113,29,29);
			background: linear-gradient(90deg, rgba(113,29,29,1) 0%, rgba(157,39,40,1) 50%, rgba(236,50,55,1) 100%);
		}
		.service-buttons{
			grid-template-rows:1fr;
			grid-template-columns: 1fr 1fr 1fr;
			max-width: 1140px;
			margin:auto;
		}
	}
</style>
<svelte:head>
	<title>Aries Mechanical Hvac A/C Furnace Installation & Repair Company</title>
	<meta name="description" content="Customers rely on Aries Mechanic Inc. HVAC in Newark, IL to get the job done in a high-degree of professionalism and workmanship.">
</svelte:head>
<Hero
		heroImage="/assets/images/heros/cooling.jpg"
		heroTitle="Providing Your Family"
		heroBigText="Affordable & Quality HVAC Services For Over 30 Years"
		heroText=" Your Hvac | A/C | Furnace Installation & Repair Company">
	<p>Our customers are treated as if they are part of our family. We respect our customers and listen to their needs. We provide our customers with honesty and reliability that they deserve. Aries Mechanical, Inc. is known for our quality craftsmanship at competitive prices.</p>
	<a class="btn btn-outline-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<div class="service-btns-bg">
	<section class="service-buttons">
		<ServiceBtn serviceBtnBg="#711D1D" serviceLink="/contact" serviceTitle="Schedule Service" serviceIcon="/assets/images/icons/repairs-icon.png" serviceIconAlt="Hvac a/c furnace Repairs Icon">Service</ServiceBtn>
		<ServiceBtn serviceBtnBg="#9D2728" serviceLink="/contact" serviceTitle="Schedule Replacement" serviceIcon="/assets/images/icons/replacements-icon.png" serviceIconAlt="Hvac a/c furnace Replacements Icon">Installation</ServiceBtn>
		<ServiceBtn serviceLink="/contact" serviceTitle="Setup Annual Maintenance" serviceIcon="/assets/images/icons/maintenance-icon.png" serviceIconAlt="Hvac a/c furnace Maintenance Icon">Maintenance</ServiceBtn>
	</section>
</div>

<section class="about-section">
	<div class="container">
		<h2 class="text-center">Aries Mechanical, Inc. Heating & Cooling in Newark, IL</h2>
		<div class="row">
			<div class="col-xs-12 col-sm-6">
				<p>Aries Mechanical, Inc. is proud to serve the following communities:  Newark, Oswego, Plano, Yorkville, and Sandwich, IL with more than 25 years experience in the heating and air conditioning mechanical industry.</p>
			</div>
			<div class="col-xs-12 col-sm-6">
				<p>We are the HVAC contractor that specializes in residential heating and air conditioning solutions. If your looking to replace a current furnace or Air Conditioner or repair an exsisting call Aries Mechanical Inc.</p>
			</div>
		</div>
	</div>
</section>
<Divider>
	<h2>Specials</h2>
</Divider>
<section class="coupon-section">
	<div class="container">
		<div class="row">
			<div class="col-xs-12 col-sm-4">
				<Coupon couponPrice="$85 Flat-rate" couponTitle="Gas Furnace or A/C Cleaning" couponSubtitle="with FREE Safety Inspection!" couponText="Not to be combined with any other discount or offer" couponExpires="Never"/>
			</div>
			<div class="col-xs-12 col-sm-4">
				<Coupon couponPrice="$200 Off" couponTitle="Any New Furnace or A/C Installation" couponSubtitle="" couponText="Not to be combined with any other discount or offer" couponExpires="Never"/>
			</div>
			<div class="col-xs-12 col-sm-4">
				<Coupon couponPrice="$50 off" couponTitle="Any Service Repair on Furnace or A/C" couponSubtitle="" couponText="Not to be combined with any other discount or offer" couponExpires="Never"/>
			</div>
		</div>
		<div class="text-center specials-button">
			<a class="btn btn-primary btn-lg text-center" href="special" title="See Our Specials">See All Of Our Current Hvac Specials</a>
		</div>
	</div>
</section>
<TraneBanner />
<Divider>
	<h2>Heating & Cooling Services</h2>
</Divider>
<ServicesGrid/>
