<template>
  <div id="app">
    <NavBar id="nav-bar" />
    <router-view />
  </div>
</template>

<script>
import NavBar from './components/NavBar';

export default {
  name: 'App',
  components: { NavBar },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  scroll-behavior: smooth;
}

a {
  font-weight: bold;
  color: #2c3e50;

  &.router-link-exact-active {
    color: #42b983;
  }
}

#nav-bar {
  position: fixed;
  top: 0;
  width: 100%;
}
</style>
