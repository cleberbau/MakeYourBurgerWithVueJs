<template> 
  <Navbar/>
  <RouterView />
  <Footer />
 </template>

<script>
/*import { RouterLink, RouterView } from 'vue-router'
import About from './views/About.vue';
import Home from './views/Home.vue';*/
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';

export default {
  components:{
    Navbar,
    Footer
  }
}

</script>
