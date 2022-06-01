<template>
  <div id="app">
    <Header />
    <SecondContent />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import SecondContent from './components/SecondOjtContent.vue';

export default{
  
  components:{
    Header,
    Footer,
    SecondContent
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
}
* {
    margin: 0;
    padding: 0;
} 
</style>
