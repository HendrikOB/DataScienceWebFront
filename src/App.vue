<template>
  <div id="app">
    <Header msg="Welcome to Your Vue.js App"/>
    <Promo />
    <Speakers />
    <Whatis />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Promo from './components/Promo.vue'
import Speakers from './components/Speakers.vue'
import Whatis from './components/Whatis.vue'
import Footer from './components/Footer.vue'



export default {
  name: 'app',
  components: {
    Header,
    Promo,
    Speakers,
    Whatis,
    Footer
  }
}
</script>
