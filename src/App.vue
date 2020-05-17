<template>
  <div id="app">
    <navbar />
    <top />
    <works />
    <about />
    <blog />
    <contact />
  </div>
</template>

<script>
  import navbar from './components/Navbar.vue'
  import top from './views/top.vue'
  import works from './views/works.vue'
  import about from './views/about.vue'
  import blog from './views/blog.vue'
  import contact from './views/contact.vue'

  export default {
    name: 'App',
    components: {
      top,
      works,
      about,
      blog,
      contact,
      navbar
    }
  }

</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

  body {
    font-family: 'Roboto', sans-serif;
  }

  #app {
    text-align: center;
    color: #2c3e50;
    margin-top: 40px;
  }

  .custom-nav {
    overflow-x: hidden !important;
  }

  #top,
  #works,
  #about,
  #blog,
  #contact {
    padding-top: 40px;
  }

  .ttl {
    font-size: 3rem;
  }

</style>
