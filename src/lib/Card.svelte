<script>
    export let title = "";
    export let description = "";
    export let price = 0;
</script>

<div class="card">
    <h2>{title}</h2>
    <p>{description}</p>
    <p>${price}</p>
</div>

<style>
    .card {
        border: 1px solid tomato;
        width: 500px;
    }
    h2 {
        font-size: 30px;
        font-weight: var(--font-weight-8);
    }
    p {
        font-weight: var(--font-weight-4);
    }
</style>