<script>
    import Nav from './Nav.svelte'
</script>

<header class="container">
    <span class="logo">chris bernhard</span>
    <Nav />
</header>


<style>
    header {
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
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