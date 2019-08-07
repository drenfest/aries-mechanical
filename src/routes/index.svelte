<script>
	import Hero from '../components/Hero.svelte';
	import ServiceBtn from '../components/ServiceBtn.svelte';
	import Divider from '../components/Divider.svelte';
	import Coupon from '../components/Coupon.svelte';
	import TraneBanner from '../components/TraneBanner.svelte';
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
<!--OLD HOMEPAGE CONTENT START-->
<!--<h2 class="section-heading">Heating</h2>-->
<!--<h3 class="card-title">T_XR95</h3>-->
<!--<p class="card-text">The XR95 forced air heating gas furnace offers our highest energy efficiency in single-stage performance, which means more of your energy dollars go toward actually heating your home. Featuring a 95% AFUE rating, the XR95 is constructed with high-quality components for long-lasting performance and durability.</p>-->
<!--<h2 class="section-heading">Cooling</h2>-->
<!--<h3 class="card-title">H3S9V2</h3>-->
<!--<p class="card-text">The new S9V2 furnace is more efficient in both heating and cooling, offers quiet operation, and maintains the DNA that Trane is known for: quality and reliability. The S9V2 is rated at 96% gas efficiency (AFUE) providing energy savings in both winter AND summer. With stainless steel primary and secondary heat exchangers you can count on a consistent flow of warm, comfortable air with quiet operation.</p>-->
<!--<h3 class="card-title">TXR-AIR-CONDITIONER</h3>-->
<!--<p class="card-text">The single-stage XR14 heat pump offers up to 14.50 SEER/8.50 HSPF, available in 1.5-5 ton models, making it an energy-efficient choice for home comfort. This unit features a Spine Fin™ coil and a Climatuff® compressor to handle any outdoor climate conditions and prevent interior temperature swings.</p>-->
<!--<h2 class="section-heading">Humidification</h2>-->
<!--<h3 class="card-title">Aprilaire 700</h3>-->
<!--<p class="card-text">Powered to run when your heating and cooling system cycles, the Aprilaire 700 whole-house powered humidifier delivers up to 18 gallons of moisture into the air each day. The systems distribution tray helps ensure that moisture is distributed evenly and the device is backed by a 5-Year Warranty.</p>-->
<!--<h3 class="card-title">Aprilaire 1700 Series</h3>-->
<!--<p class="card-text">Aprilaire whole-house dehumidifiers work throughout your entire home. The 1700 series features automatic control, so there’s never a need to manually operate your dehumidifier. There’s no messy tanks to empty or clean and with the 1700 series, the system automatically senses moisture level and maintains optimum humidity level in your home, never too much or too little.</p>-->
<!--<h2 class="section-heading">Air Cleaning</h2>-->
<!--<h3 class="card-title">Central Air Cleaning</h3>-->
<!--<p class="card-text">Energy efficient and fresh air ventilation systems are affordable, effective and provide optimum whole-house ventilation you deserve. Energy efficient ventilation systems help reduce condensation and excess moisture while fresh air systems works with your existing heating and cooling fan system to deliver outside air to your home.</p>-->
<!--<h3 class="card-title">Whole House UV Air Purification System</h3>-->
<!--<p class="card-text">The Guardian Air Reflective Electro Magnetic Energy purification system purifies indoor air with naturally-occurring oxidizers like ionized hydro-peroxides. The Guardian Air is today’s most advanced technology for boosting airborne oxidizers, critical to your family’s health</p>-->
	<!--OLD HOMEPAGE CONTENT END-->
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
