<template>
  <div id="app">
    <Header msg="Welcome to Your Vue.js App"/>
    <Promo></Promo>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Promo from './components/Promo.vue'


export default {
  name: 'app',
  components: {
    Header,
    Promo
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
