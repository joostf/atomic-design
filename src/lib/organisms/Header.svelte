<script>
  import { FdndLogo, Nav, SearchForm } from '$lib/index.js'

</script>

<header>
  <FdndLogo />

  <Nav />

  <SearchForm />
</header>


<style>
  header {
    display: flex;
    flex-flow: row nowrap;
    justify-content: flex-start;
    align-items: center;
    gap:1rem;
  }
</style>