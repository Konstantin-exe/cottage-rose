<template>
  <div id="app">
    <NavBar id="nav-bar" />
    <router-view />
    <Footer />
  </div>
</template>

<script>
import NavBar from './components/NavBar';
import Footer from './components/Footer';

export default {
  name: 'App',
  components: { NavBar, Footer },
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
