<template>
  <nav>
    <router-link :to="{ name: 'Home' }">Projects</router-link>
    <router-link :to="{ name: 'AddProject' }">Add New Project</router-link>
  </nav>
</template>

<script>
  export default {

  }
</script>

<style>
  nav {
    text-align: center;
    margin: 40px auto;
  }

  nav a {
    display: inline-block;
    text-decoration: none;
    margin: 0 1rem 0rem;
    color: #999;
    font-size: 18px;
    padding: 1rem 2rem;
    border-radius: 2rem;
    border: 2px solid transparent;
  }

  nav a:hover {
    background: white;
    border: 2px solid #00ce89;
  }

  a.router-link-active {
    border: 2px solid #00ce89;
    /* padding: 1rem; */
    background: white;
  }

</style>
