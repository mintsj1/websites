<script>
    let { data } = $props();
</script>

<h2>Bloggers Contents</h2>

<nav>
    {#each data.post as post}
    <a href="/blog/{post.title}">{post.title}</a>
    {/each}
</nav>

<style>
    nav {
        display: flex;
        flex-direction: column;
    }
</style>