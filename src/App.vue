<template>
  <div id="app">
    <Header />
    <main>
      <HomePage />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import HomePage from './components/HomePage.vue';

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    HomePage,
  },
};
</script>

<style>
/* Add any necessary global styling here */
</style>
