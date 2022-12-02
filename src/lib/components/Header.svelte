<script>
    import Nav from './Nav.svelte'
</script>

<header class="container">
    <h1>chris bernhard</h1>
    <Nav />
</header>


<style>
    header {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        padding: 2.5rem 0;
    }
    h1 {
        font-weight: 700;
        letter-spacing: 1.5px;
    }
</style>