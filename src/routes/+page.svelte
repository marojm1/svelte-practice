<!--Home page-->
<script>
    import Header from "$lib/Header.svelte"
    import Footer from "$lib/Footer.svelte"
    import homepic from "$lib/cheetah.jpg"
</script>

<Header headingTitle ="Home page"/>
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

