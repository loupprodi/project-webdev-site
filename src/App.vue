<template>
  <div id="app">
    <appHeader />
    <router-view path="$router.key"/>
    <!-- <homePage /> -->
    <appFooter/>
  </div>
</template>

<script>
import './styles/global.css';
import appHeader from './components/Header.vue';
import appFooter from './components/Footer.vue';
// import homePage from './pages/Home.vue';

export default {
  name: 'App',
  components: { 
    appHeader,
    // homePage,
    appFooter
  }
}
</script>