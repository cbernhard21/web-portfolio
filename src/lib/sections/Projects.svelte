<script>
    import { projects } from '$lib/data/data.json';

</script>



<div class="projects-wrapper mb-8">
    <section class="projects container">
        <h2 class="section-title">Projects Section</h2>
        <div class="projects-grid">
            {#each projects as project }
                <article>
                    <h3>{project.name}</h3>
                    <ul class="tech-list">
                        {#each project.technology as technology }
                            <li>{technology}</li>
                        {/each}
                    </ul>
                </article>            
            {/each} 
            </div>
    </section>
</div>

<style>

    .projects {
        border-top: 2px solid var(--white);
        padding: 2rem 2rem 0;
    }

    .projects-grid {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 5rem;
    }


    .tech-list {
        list-style-type: none;
        display: flex;
        gap: 2rem;
    }

</style>

