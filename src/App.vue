<script>

import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Firstsection from './components/Firstsection.vue'
import Secondsection from './components/Secondsection.vue'


export default {
  components:{
    Header,
    Firstsection,
    Secondsection,
    Main,
    Footer
  }

}
</script>
<template>

  <Header/>
  <Firstsection />
  <Secondsection />


  <Main/>
  <Footer/>

  
</template>


<style scoped>

</style>