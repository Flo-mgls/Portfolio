<template>
  <!-- HEADER -->
  <header>
    <NavBar />
    <Header />
  </header>
  <!-- END HEADER -->
  <!-- MAIN -->
  <main>
    <Intro />
    <Offers />
    <Skills />
    <Services />
    <Portfolio />
  </main>
  <!-- END MAIN -->
  <!-- FOOTER -->
  <footer>
    <Contact />
    <Footer />
  </footer>
  <!-- END FOOTER -->
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Header from "./components/Header.vue";
import Intro from "./components/Intro.vue";
import Offers from "./components/Offers.vue";
import Skills from "./components/Skills.vue";
import Services from "./components/Services.vue";
import Portfolio from "./components/Portfolio.vue";
import Contact from "./components/Contact.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Header,
    Intro,
    Offers,
    Skills,
    Services,
    Portfolio,
    Contact,
    Footer,
  },
};
</script>

<style lang="scss">
#app {
  font-family: "Quicksand", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #455a64;
}
</style>
