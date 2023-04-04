<script>
  import NavBar from './components/NavBar.vue';
  import IntroSection from './components/IntroSection.vue';
  import USP from './components/USP.vue';
  export default {
    name: "App",
    components: {
      NavBar,
      IntroSection,
      USP,
    }
  }
</script>

<template>
  <NavBar/>
  <IntroSection/>
  <USP/>
</template>

<style scoped src="./assets/main.css"></style>