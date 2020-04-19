<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">SURF TRIPS</router-link>
      <router-link to="/about">CAMPS</router-link>
      <router-link to="#">CONTACT</router-link>
      <router-link to="#">SHOP</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    text-decoration: none;
    margin-right: 80px;
    color: #000000;

    &.router-link-exact-active {
      color: #E12106;
    }
  }
}
</style>
