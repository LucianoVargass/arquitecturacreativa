<template>
  <v-app>
  
    <v-main>
      <HelloWorld/>
      <Home/>
      <Hacemos/>
    </v-main>
   <Footer/>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Footer from './components/Footer';
import Home from './components/Home';
import Hacemos from './components/Hacemos';




export default {
  name: 'App',

  components: {
    HelloWorld,
    Footer,
    Home,
    Hacemos,

  },

  data: () => ({
    //
  }),
};
</script>
