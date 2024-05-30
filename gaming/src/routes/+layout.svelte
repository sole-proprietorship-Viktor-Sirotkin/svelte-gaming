<script>
    import Title from "$lib/Title.svelte";
</script>

<header>
    <Title title="Svelte Gaming" />
</header>

<nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
    <a href="/guides">Guides</a>
</nav>

<main>
    <slot />
</main>

    <footer>
        Copyright 2024 Svelte Gaming
    </footer>

<style>
    header {
        display: flex;
        justify-content: center;
    }
    main {
        max-width: 960px;
        margin: 20px auto;
        text-align: center;
    }
    footer {
        text-align: center;
    }
    nav {
        margin-top: 10px;
        text-align: center;
    }
</style>
