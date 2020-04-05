<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100vh;
}
#nav {
  a {
    font-weight: bold;
    color: #00000080;
    &.router-link-exact-active {
      color: #00000040;
    }
  }
}
</style>
