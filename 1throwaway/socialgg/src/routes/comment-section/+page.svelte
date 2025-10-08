<script>
import Comment from '$lib/components/comment';
let { data } = $props();
</script>

{#each data.comments as comment}
    <Comment data={comment} />
{/each}