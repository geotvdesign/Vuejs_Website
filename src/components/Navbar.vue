<template>
  <div>
    <nav class="navbar navbar-expand  navbar-dark bg-dark fixed-top">
      <div class="collapse navbar-collapse justify-content-center custom-nav" id="navbarSupportedContent">
        <div class="navbar-nav">
        <a v-scroll-to="'#top'">home</a>
          <a v-scroll-to="'#works'">works</a>
          <a v-scroll-to="'#about'">about</a>
          <a v-scroll-to="'#blog'">blog</a>
          <a v-scroll-to="'#contact'">contact</a>
        </div>
      </div>
    </nav>
  </div>
</template>

<style scoped>
  .navbar {
    height: 40px;
    filter: drop-shadow(0 5px 10px rgba(0, 0, 0, 0.6));
  }

  .custom-nav {
    overflow-x: scroll;
    overflow-y: hidden;
    flex-wrap: nowrap;
  }

  .navbar-nav {
    height: 40px;
    color: aliceblue;
  }

  .navbar-nav a {
    width: 100px;
    padding-top: 9px;
    padding-bottom: 10px;
  }

  .navbar-nav a:hover {
    background-color: darkgray;
  }

</style>
