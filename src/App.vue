<script>
import Footer from './components/Footer.vue';
import Nav from './components/Nav.vue';
import SectionHome from './components/SectionHome.vue'
import SectionTree from './components/SectionTree.vue';
import SectionTwo from './components/SectionTwo.vue';

export default {
  name: 'App',
  components: {
    SectionHome,
    Nav,
    SectionTwo,
    SectionTree,
    Footer
}
}
</script>

<template>
  <Nav />
  <SectionHome />
  <br>
  <SectionTwo />
  <br>
  <SectionTree />
  <Footer />

</template>

<style>

*{
  background-color: #101827;
}

</style>
