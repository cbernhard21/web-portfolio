<script>
    import { skills } from '$lib/data/data.json';
</script>

<div class="skills-wrapper mb-8">
    <section class="skills container">
        <h2 class="section-title">Knowledge</h2>
        <div class="skills-grid">
        {#each skills as skill }
            <article>
                <h3>{skill.skill}</h3>
                <p>{skill.details}</p>
            </article>            
        {/each} 
        </div>
       
    </section>
</div>

<style>
    .skills {
        border-top: 2px solid var(--white);
        padding: 2rem 2rem 0;
    }
    .skills-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(10px, 350px));
        gap: 6rem 2rem;
    }

    article {
        max-width: 50ch;
    }

    h3 {
        font-size: 2.6rem;
        margin-bottom: 1.6rem;
        font-weight: 400;
        letter-spacing: 1.2px;
    }

    p {
        font-size: 1.6rem;
    }




</style>