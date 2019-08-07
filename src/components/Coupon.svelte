<script>
    export let couponPrice;
    export let couponTitle;
    export let couponSubtitle;
    export let couponText = "Not to be combined with any other discount or offer";
    export let couponExpires;
</script>
<style>
    .coupon{
        padding-bottom:0;
        min-height:300px;
    }
    .card-title{
        color: var(--primary-color);
    }
    .card-footer{
        margin-bottom: 0px;
    }
    .card-subtitle{
        font-size:1rem;
        margin-bottom:1rem;
    }
</style>
<div class="coupon card text-center">
    <div class="card-body">
        <h2 class="card-title">{couponPrice}</h2>
        <h3 class="card-subtitle">{couponTitle} <br> {couponSubtitle}</h3>
        <p class="card-text">{couponText}</p>
    </div>
    <p class="card-footer">
        <strong>Expires:</strong> {couponExpires}
    </p>
</div>
