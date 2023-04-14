<template>
  <div id="app">
    <main-header></main-header>
    <main-body></main-body>
    <main-footer></main-footer>
  </div>
</template>

<script>
import MainHeader from './components/main_header.vue'
import MainBody from './components/main_body.vue'
import MainFooter from './components/main_footer.vue'
export default {
  name: 'App',
  components: {
    MainHeader,
    MainBody,
    MainFooter,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
