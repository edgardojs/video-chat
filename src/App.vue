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
  color: #f8f8f8;
  height: 100vh;
}
#nav {
  a {
    font-weight: bold;
    color: #f8f8f880;
    &.router-link-exact-active {
      color: #f8f8f840;
    }
  }
}
</style>
