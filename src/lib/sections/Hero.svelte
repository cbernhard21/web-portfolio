<script>
    import rings from '$lib/images/pattern-rings.svg'
    import profile from '$lib/images/image-profile-desktop.webp'

</script>


<div class="hero-wrapper">
    <section class="container hero">
        <img src="{rings}" alt="Rings that make a pattern for the background" class="background">
        <img src="{profile}" alt="Profile of Christopher Bernhard" class="profile-pic">
        <h1>Nice To Meet You! <span class="block">I'm <span class="underline">Chris Bernhard</span>.</span></h1>
        <p>
            Based in Chicago, IL, I'm a front-end developer passionate about building accessible web apps that users love.
        </p>
        <a href="/" class="btn">Contact Me</a>
        
    </section>
</div>

<style>
    .hero-wrapper {
        height: 90vh;
    }

    .hero {
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        position: relative;
        gap: 5rem;
    }

    h1 {
        font-size: 7rem;
        font-weight: 400;
    }

    p {
        font-size: 1.6rem;
        max-width: 40ch;
    }

    .background {
        position: absolute;
        max-width: 50rem;
        top: 100px;
        left: -200px;
    }

    .profile-pic {
        position: absolute;
        top: 0;
        right: 0;
        width: 500px;
        z-index: -999;
    }
</style>