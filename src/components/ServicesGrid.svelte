<script>

</script>
<style>
    .grid{
        display:grid;
        grid-template-columns: 1fr;
        grid-gap:1rem;
        text-align:center;
        padding:3rem 1rem;
    }
    .service{
        display:flex;
        flex-direction:column;
        justify-content:center;
        min-height:300px;
        max-height:300px;
        font-size:2rem;
        color:white;
        font-weight:bold;
        background-color:rgba(0,0,0,.4);
        background-blend-mode:overlay;
        background-position:center;
        background-size:cover;
        width:100%;
    }
    .service.service-heating{
        background:url(/assets/images/services/service1.jpg)no-repeat;
    }
    .service.service-ac{
        background:url(/assets/images/services/service2.jpg)no-repeat;
    }
    .service.service-air-cleaning{
        background:url(/assets/images/services/service3.jpg)no-repeat;
    }
    .service.service-res-hvac{
        background:url(/assets/images/services/service4.jpg)no-repeat;
    }
    .service.service-humidify{
        background:url(/assets/images/services/service-humidification.jpg)no-repeat;
    }
    .service.service-thermostats{
        background:url(/assets/images/services/service5.jpg)no-repeat;
    }
    @media screen and (min-width:768px){
        .grid{
            grid-template-columns: 1fr 1fr;
        }
    }
    @media screen and (min-width:992px){
        .grid{
            grid-template-columns: 1fr 1fr 1fr;
        }
    }
</style>
<section class="services-grid">
    <div class="container">
        <div class="grid">
            <a class="service service-heating" title="Read About Our Heating Services" href="/heating">Heating</a>
            <a class="service service-ac" title="Read About Our Air Conditioning" href="/conditioning">Air Conditioning</a>
            <a class="service service-air-cleaning" title="Read About Our Air Cleaning And Purifying Services" href="/air-cleaning">Air Cleaning</a>
            <a class="service service-res-hvac" title="Read About Our Residential Services" href="">Residential Hvac</a>
            <a class="service service-thermostats" title="Read About Programmable Thermostats" href="/programmable">Thermostats</a>
            <a class="service service-humidify" title="Read About Our Furnace Repair Services" href="">Furnace Repair</a>
        </div>
    </div>
</section>
