<template>
  <main>
    <NavBar />
    <HomePage />
  </main>
</template>

<script>
/* eslint-disable */
import HomePage from './components/HomePage.vue';
import NavBar from './components/navbar/NavBar.vue';

export default {
  name: 'App',
  components: {
    HomePage,
    NavBar,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 60px;
  background-color: #1c2e4a;
}
</style>
