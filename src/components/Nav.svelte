<script>
	export let segment;
</script>

<style>

</style>
<section class="container">
	<nav>
		<ul class="nav navbar nav-pills nav-fill">
			<li class="nav-item dropdown">
			<a class="nav-link dropdown-toggle" href='#' role="button" aria-haspopup="true" aria-expanded="false" data-toggle="dropdown" title="Heating">Heating</a>
				<div class="dropdown-menu">
					<h3>Heating</h3>
					<div class="row">
						<div class="col-md-6">
							<a class='dropdown-item {segment === "heating" ? "active" : ""}' href='heating' title="Heating">Heating</a>
						</div>
						<div class="col-md-6">Background Image</div>
					</div>
				</div>
			</li>
			<li class="nav-item dropdown">
				<a class="nav-link dropdown-toggle" href='#' role="button" aria-haspopup="true" aria-expanded="false" data-toggle="dropdown" title="Cooling">Cooling</a>
				<div class="dropdown-menu">
					<h3>Cooling</h3>
					<div class="row">
						<div class="col-md-6">
							<a class='dropdown-item {segment === "cooling" ? "active" : ""}' href='cooling' title="Cooling">Cooling</a>
						</div>
						<div class="col-md-6">Background Image</div>
					</div>

				</div>
			</li>
			<li class="nav-item"><a rel=prefetch class='{segment === "humidification" ? "active" : ""}' href='humidification' title="Humidification">Humidification</a></li>
			<li class="nav-item"><a rel=prefetch class='{segment === "reviews" ? "active" : ""}' href='reviews' title="Reviews">Reviews</a></li>
			<li class="nav-item"><a rel=prefetch class='{segment === "specials" ? "active" : ""}' href='specials' title="Specials">Specials</a></li>
			<li class="nav-item"><a rel=prefetch class='{segment === "contact" ? "active" : ""}' href='contact' title="Contact Us">Contact</a></li>
		</ul>
	</nav>
</section>

