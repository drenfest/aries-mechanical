<script>
    export let content="";
    import {onMount} from 'svelte';
    onMount(()=>{
        fetch('/nn.php').then(function(response) {
            response.text().then(function(text) {
                content = text;
            })
        });
    });

</script>
<style>
    .nn-section{
        padding:2rem;
    }
</style>
<section class="nn-section container">
    {@html content}
</section>
