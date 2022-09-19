<script>

const links = ['Work', 'About', 'Contact'];
const workDD = ['Projects', 'Blogs']
const aboutDD = ['Bio', 'Uses']
const contactDD = ['Social Media', 'Email']
</script>

<ul>
  {#each links as link }
  <li>
    {link}
  </li>
  {/each}
</ul>

<style>
  ul {
    display: flex;
    flex-direction: row;
    list-style: none;
    gap: 1rem;
  }

  li:hover{
    cursor: pointer;
    border-radius: .3rem;
    background-color: rgb(140, 140, 140);
  }
</style>