<template>
  <div id="app">
    <Navbar />
      <div class='content'>
        <router-view />
      </div>
    <Footer />
  </div>
</template>

<script>
import Navbar from './layout/Navbar/index.vue';
import Footer from './layout/Footer/index.vue';

export default {
  name: 'app',
  components: {
    Navbar,
    Footer
  }
}
</script>

<style lang="scss">
  @import './styles/index.scss';
</style>
