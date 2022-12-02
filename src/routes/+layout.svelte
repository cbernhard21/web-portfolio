<script>
    import '$lib/css/global.css'
    import Footer from '../lib/components/Footer.svelte';
    import Header from '../lib/components/Header.svelte';
</script>

<svelte:head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Alexandria:wght@300;400;700&display=swap" rel="stylesheet">
</svelte:head>

<Header />

<slot></slot>

<Footer />