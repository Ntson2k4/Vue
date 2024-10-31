<script>
import BodyS from './components/BodyS.vue';
import FooterS from './components/FooterS.vue';
import HeaderS from './components/HeaderS.vue';

export default {
  name: 'App',
  components: {
    HeaderS,
    BodyS,
    FooterS,
  }
}
</script>

<template>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
  <div id="app">
    <HeaderS />
    <BodyS />
    <FooterS />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 0px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
