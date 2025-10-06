<script>
    import Post from '$lib/components/post.svelte';
    let posts = [
    {
        username: "sunny_skies",
        avatar: "https://tse2.mm.bing.net/th/id/OIP.Ai9h_6D7ojZdsZnE4_6SDgAAAA?cb=12&rs=1&pid=ImgDetMain&o=7&rm=3",
        postDate: "2025-10-01",
        postText: "Loving the spring vibes in Dunedin 🌸",
        likes: 120
    },
    {
        username: "code_wizard",
        avatar: "https://tse2.mm.bing.net/th/id/OIP.Ai9h_6D7ojZdsZnE4_6SDgAAAA?cb=12&rs=1&pid=ImgDetMain&o=7&rm=3",
        postDate: "2025-10-02",
        postText: "Just solved a tricky bug in my JavaScript project. Feeling accomplished!",
        likes: 89
    },
    {
        username: "travel_bug",
        avatar: "https://example.com/avatar3.jpg",
        postDate: "2025-10-03",
        postText: "Exploring the Otago Peninsula today. Stunning views!",
        likes: 145
    },
    {
        username: "coffee_lover",
        avatar: "https://example.com/avatar4.jpg",
        postDate: "2025-10-04",
        postText: "Flat white from my favorite café ☕️",
        likes: 76
    },
    {
        username: "bookworm88",
        avatar: "https://example.com/avatar5.jpg",
        postDate: "2025-10-05",
        postText: "Just finished reading 'The Midnight Library'—highly recommend!",
        likes: 102
    },
    {
        username: "fitness_freak",
        avatar: "https://example.com/avatar6.jpg",
        postDate: "2025-10-06",
        postText: "Morning run by the beach. Nothing beats that fresh air!",
        likes: 134
    },
    {
        username: "tech_guru",
        avatar: "https://example.com/avatar7.jpg",
        postDate: "2025-10-06",
        postText: "Trying out the new JavaScript framework—so far, so good!",
        likes: 98
    },
    {
        username: "artsy_annie",
        avatar: "https://example.com/avatar8.jpg",
        postDate: "2025-10-07",
        postText: "Painted a new landscape piece today. Feeling inspired 🎨",
        likes: 157
    },
    {
        username: "gamer_zone",
        avatar: "https://example.com/avatar9.jpg",
        postDate: "2025-10-07",
        postText: "Late-night gaming session with friends—epic wins all around!",
        likes: 110
    },
    {
        username: "nature_nate",
        avatar: "https://example.com/avatar10.jpg",
        postDate: "2025-10-07",
        postText: "Spotted a rare bird in the garden this morning 🐦",
        likes: 88
    }
];
</script>

{#each posts as post}
    <Post postData={post} />
{/each}


<style>
    :global(body) {
        font-family: Verdana, Geneva, Tahoma, sans-serif;
    }
</style>