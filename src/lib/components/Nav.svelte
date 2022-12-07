<nav class="nav-main">
    <ul class="nav-list">
        <li class="nav-item"><a href="/" class="nav-link">Home</a></li>
        <li class="nav-item"><a href="/projects" class="nav-link">Projects</a></li>
        <li class="nav-item"><a href="#contact" class="nav-link">Contact</a></li>
    </ul>
</nav>

<style>
    .nav-list {
        list-style-type: none;
        display: flex;
        flex-direction: row;
        gap: 4rem;
    }

    .nav-link {
        display: inline-block;
        font-size: 1.6rem;
        letter-spacing: 1.2px;
        transition: all .2s ease-in-out;
    }

    .nav-link:hover {
        color: var(--accent);
    }
</style>

