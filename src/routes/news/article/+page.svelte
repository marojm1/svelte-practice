<script>
  export let data;
  const posts = data.posts;
  import Post from "../lib/Post.svelte";
  import Navigation from "../lib/Navigation.svelte";
</script>

<h2>This is a news article</h2>
{#each posts as post}
  <Post> {post}</Post>  
{/each}


