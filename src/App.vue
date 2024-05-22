<!-- eslint-disable -->
<template>
  <div id="app">
    <Header />
    <main>
      <About />
      <Services />
      <Contact />
    </main>

  </div>
</template>

<script>
import Header from './components/Header.vue';
import About from './components/About.vue';
import Services from './components/Services.vue';
import Contact from './components/Contact.vue';

export default {
  name: 'App',
  components: {
    Header,
    About,
    Services,
    Contact
  }
}
</script>

<style>
/* Importowanie pliku CSS */
@import './styles/styles.css';
</style>


