<script>
  export let data;
  const posts = data.posts;
  import Post from "$lib/Post.svelte";
  
</script>

<h2>This is a news article</h2>
{#each posts as post}
  <Post {post} />  
{/each}


