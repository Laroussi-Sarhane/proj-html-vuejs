<script>

import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
import Firstsection from './components/Firstsection.vue'
import Secondsection from './components/Secondsection.vue'
import Thirdsection from './components/Thirdsection.vue'
import Foursection from './components/Foursection.vue'
import Fivesection from './components/Fivesection.vue'


export default {
  components:{
    Header,
    Firstsection,
    Secondsection,
    Thirdsection,
    Foursection,
    Fivesection,
    Footer
  }

}
</script>
<template>

  <Header/>
  <Firstsection />
  <Secondsection />
  <Thirdsection />
  <Foursection />
  <Fivesection/>




  
  <Footer/>

  
</template>


<style scoped>

</style>