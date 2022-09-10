<script>
  import Time from './navComp/time.svelte'
  
  const links = ['Work', 'About', 'Contact'];
  
</script>

<nav class="navBar">
  <ul>
    {#each links as link}
      <li>{link}</li>  
    {/each}
  </ul>
  <Time/>
</nav>


<style>
  
  .navBar {
    display: flex;
    background-color: rgb(190, 190, 190);
    justify-content: space-between;
    box-shadow:  0px 0px 5px rgb(0, 0, 0);
    
  }
  ul {
    display: flex;
    flex-direction: row;
    list-style: none;
    gap: 0.5rem;

  }
  li{
    padding: .15rem 1rem ;
    
  }

  li:hover{
    cursor: pointer;
    border-radius: .3rem;
    background-color: rgb(140, 140, 140);
  }
</style>