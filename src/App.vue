<template>
  <NavbarComp :logo="logo_src" :alt="app_name"/>
  <router-view/>
  <FooterComp/>
</template>

<script>

import NavbarComp from './components/NavbarComp.vue';
import FooterComp from './components/FooterComp.vue';

export default {
    components: {
        NavbarComp,
        FooterComp
    },
    data() {
      return {
        logo_src: '/img/Hamburger2.jpg',
        app_name: 'awesomeburger'
      }
    }
}

</script>

<style>

  * {
    font-family: Helvertica;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  .main-container {
    margin: 50px;
    min-height: 300px;
  }

  h1 {
    text-align: center;
    font-size: 35px;
    padding-bottom: 50px;
    color: #003566;
  }
</style>
