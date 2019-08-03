<script>
	export let segment;
</script>

<style>
	.bg-dark{}
	.bg-image{
		width:300px;
		padding:2rem;
		align-self:center;
		display:flex;
		flex-direction:column;
		justify-content:center;
		background-color:grey;
		height:100%;
		color:#ffffff;
		text-align:center;
	}
	.dropdown-menu{
		min-width:600px;
		margin:0;
		padding:0;
	}
	.row{
		padding:2rem;
		margin:0;
	}
	.col-6{
		justify-content:center;
		display:flex;
		flex-direction:column;
	}
</style>
<section class="bg-dark">
	<nav class="container d-xs-none d-sm-block">
		<ul class="nav navbar navbar-dark nav-fill nav-pills justify-content-between">
			<li class="nav-item dropdown">
			<a class="nav-link dropdown-toggle" href='#' role="button" aria-haspopup="true" aria-expanded="false" data-toggle="dropdown" title="Heating">Heating</a>
				<div class="dropdown-menu">
					<div class="row">
							<div class="col-6">
								<h3>Heating</h3>
								<a class='dropdown-item {segment === "heating" ? "active" : ""}' href='heating' title="Heating">Heating</a>
								<a class='dropdown-item {segment === "residential-hvac" ? "active" : ""}' href='heating' title="Residential Hvac">Residential Hvac</a>
								<a class='dropdown-item {segment === "furnace-sales" ? "active" : ""}' href='heating' title="New Furnace Installation">New Furnace Installation</a>
								<a class='dropdown-item {segment === "furnace-repair" ? "active" : ""}' href='heating' title="Furnace Repair">Furnace Repair</a>
								<a class='dropdown-item {segment === "programmable" ? "active" : ""}' href='programmable' title="Programmable Thermostats">Programmable Thermostats</a>
							</div>
							<div class="col-6">
								<div class="bg-image">
									Background Image
								</div>
							</div>
						</div>
				</div>
			</li>
			<li class="nav-item dropdown">
				<a class="nav-link dropdown-toggle" href='#' role="button" aria-haspopup="true" aria-expanded="false" data-toggle="dropdown" title="Cooling">Cooling</a>
				<div class="dropdown-menu">
					<div class="row">
						<div class="col-6">
							<h3>Cooling</h3>
							<a class='dropdown-item {segment === "cooling" ? "active" : ""}' href='cooling' title="Cooling">Cooling</a>
							<a class='dropdown-item {segment === "air-conditioning" ? "active" : ""}' href='air-conditioning' title="Air Conditioning">Air Conditioning</a>
							<a class='dropdown-item {segment === "residential-hvac" ? "active" : ""}' href='residential-hvac' title="Residential Hvac">Residential Hvac</a>
							<a class='dropdown-item {segment === "cooling" ? "active" : ""}' href='new-ac-sales' title="New A/C Installation">New A/C Installation</a>
							<a class='dropdown-item {segment === "cooling" ? "active" : ""}' href='ac-repair' title="A/C Repair">A/C Repair</a>
							<a class='dropdown-item {segment === "programmable" ? "active" : ""}' href='programmable' title="Programmable Thermostats">Programmable Thermostats</a>
						</div>
						<div class="col-6">
							<div class="bg-image">
								Background Image
							</div>
						</div>
					</div>

				</div>
			</li>
			<li class="nav-item"><a rel=prefetch class='{segment === "humidification" ? "active" : ""}' href='humidification' title="Humidification">Humidification</a></li>
			<li class="nav-item"><a rel=prefetch class='{segment === "reviews" ? "active" : ""}' href='reviews' title="Reviews">Reviews</a></li>
			<li class="nav-item"><a rel=prefetch class='{segment === "special" ? "active" : ""}' href='special' title="Specials">Specials</a></li>
			<li class="nav-item"><a rel=prefetch class='{segment === "contact" ? "active" : ""}' href='contact' title="Contact Us">Contact</a></li>
		</ul>
	</nav>
</section>

