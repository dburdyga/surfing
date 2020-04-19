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
@import '../src/styles/styles.scss';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $black;
}

#nav {
  padding: 30px;

  a {
    font-size: 15px;
    font-weight: bold;
    text-decoration: none;
    margin-right: 80px;
    color: $black;

    &.router-link-exact-active {
      color: $red;
    }
  }
}
</style>
