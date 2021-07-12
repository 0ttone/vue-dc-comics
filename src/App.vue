<template>
  <div id="app">
        <Header/>
        <Main/>
        <BluBanner/>
        <Footer/>
    
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
import BluBanner from './components/BluBanner.vue'


export default {
  name: 'App',
  components: {
        Header,
        Main,
        BluBanner,
        Footer
    
  }
}
</script>

<style lang="scss">
@import "./style/app.scss"

</style>
