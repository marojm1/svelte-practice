<script>
    export let headingTitle;
</script>

<header>
  <h1>{headingTitle}</h1>
    <nav>
      <a  href="/" >Home</a>
      <a href ="/about">About</a>
        <a href="/contact">Contact</a>
      
    </nav>
  
</header>

<style>
    nav a {
  float: right;
  color: grey;
  text-align: center;
  padding: 2px 10px;
  font-size: 17px;
}

nav a:hover {
  background-color: #550a68;
  color: white;
}
nav{
    background-color: purple;
    padding:2em;
    border : 2px solid rgb()
    
}

</style>
