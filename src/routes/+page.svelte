<!--Home page-->
<script>
    import Header from "$lib/Header.svelte"
    import homepic from "$lib/cheetah.jpg"
    import Footer from "$lib/Footer.svelte"
    import Counter from "$lib/Counter.svelte"
    import TextInput from "$lib/Textinput.svelte"
</script>

<Header headingTitle ="Home page"/>
<Counter></Counter>
<TextInput></TextInput>
<div class = imagecontent>
   <img src={homepic} alt="a pic of a cheetah" >
</div> 
<Footer year = {2002}  />



<style>
.imagecontent{
    display:flex;
    justify-content: center;
    padding: 2em;

} 
</style>

