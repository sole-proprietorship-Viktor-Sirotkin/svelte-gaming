<script>
    export let title = 'Svelte Gaming'; // Default title
</script>

<main>
    <div class="title">
        <img src="/gaming_logo.jpg" alt="site logo">
        <h1>{title}</h1>
    </div>
</main>

<style>
    .title {
        display: flex;
    }
    .title h1 {
        margin-left: 10px;
    }
    .title img {
        width: 150px;
        height: auto;
    }
</style>
