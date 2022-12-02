<script>
    import Nav from './Nav.svelte'
</script>

<header class="container">
    <span class="logo">chris bernhard</span>
    <Nav />
</header>


<style>
    header {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        padding: 2.5rem 0;
    }
    .logo {
        font-size: 2.5rem;
        font-weight: 700;
        letter-spacing: 1.5px;

    }
</style>