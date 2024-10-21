<script>
    import Navigation from "../lib/Navigation.svelte";
</script>

<h1>I am Learning Sveltekit</h1>
<Navigation/>

<slot/>

<footer>This should be on every page, since it is in the layout file</footer>

<style>
    footer{
        padding :1em;
        background-color: #aaa
        ;
    }

  *{
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }
  
</style>