<script>
  import Time from './navComp/time.svelte';
  import Menu from './navComp/menu.svelte';

  const links = ['Work', 'About', 'Contact'];
  
</script>

<nav class="navBar">
  <Menu/>
  <Time/>
</nav>


<style>
  
  .navBar {
    display: flex;
    background-color: rgb(190, 190, 190);
    justify-content: space-between;
    box-shadow:  0px 0px 5px rgb(0, 0, 0);
    font-size: medium;
    padding: .15rem 1rem ;
  }

</style>