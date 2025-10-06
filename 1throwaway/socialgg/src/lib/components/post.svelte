<script>
    let { postData } = $props();
    console.log(postData);
</script>

<section>
    <header>
        <img src="{postData.avatar}" alt="{postData.username}">
        <h3>{postData.username}</h3>
    </header>
    <main>
    <p>{postData.postText}</p>
    </main>
    <footer>
    <p>{postData.postDate}</p>
    <p>👍 {postData.likes}</p>
    </footer>
</section>

<style>
    section {
        border: 1px solid #ccc;
        background-color: #eee;
        border-radius: 1rem;
        
    }
    header {
        display: flex;
    }
    img {
        max-width: 5rem;
        margin: 10px 15px 15px 10px;
    }
    main {
        margin-top: 1em;
    }
</style>
