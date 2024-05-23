<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/contact">Contact</router-link>
  </nav>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Poppins;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
}

nav {
  padding: 30px;

  a {
    font-weight: lighter;
    color: white;

    &.router-link-exact-active {
      color: #42b983;
      font-weight: bold;
    }
  }
}
</style>
