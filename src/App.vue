<template>
  <div id="app">
    <nav id="globalNav" class="navbar navbar-dark bg-dark navbar-expand-lg fixed-top">
      <div class="container">
        <a class="navbar-brand js-scroll-trigger" href="#page-top">Vue Profile</a>
      </div>
    </nav>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.navbar-brand {
  color: #fed136;
  font-family: 'Kaushan Script', 'Helvetica Neue', Helvetica, Arial, cursive;
}
</style>
