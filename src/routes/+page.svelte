<script>
  
  
  import Navbar from "./navbar.svelte";


</script>

<div class="desktop">
<Navbar/>
<h1>this is the desktop</h1>
</div>


<style>
  :global(*){  
    margin: 0;
    font-family: 'VT323';
  }
  :global(html, body){
    height: 100%;
    max-height: 100%;
    overflow-y: hidden;
  }
  :global(.app) {
    height: 100%;
    max-height: 100%;
    font-family: 'VT323';
  }
  .desktop{
    height: 100%;
    background-color: lightgray;
  }
</style>