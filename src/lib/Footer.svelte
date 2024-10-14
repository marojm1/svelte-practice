<script>
    export let year = 2024;
    export let pic;
    export let picname;
 
    let currentTime = new Date();
</script>
 
<div>
    <img src={pic} alt={picname}>
   
</div>
 
<p>This website is made in &copy; Web 1 {year}: The time is: {currentTime}</p>
 
<style>
    div {
        display: flex;
        flex-direction:column;
        max-width: 800px;
    }
    p {
        background-color: salmon;
        font-weight: bold;
        font-size:small;
        /* border: 10px dotted bisque; */
    }
</style>