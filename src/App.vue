<template>
  <div class="app-container">
  <Header class="header"/>
  <AboutMe class="about-me"/>
  <LeftSection class="left-section"/>
  <Skills class="skills"/>
  <!-- Footer class="footer"/ -->
  </div>
</template>

<script>
// import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
import LeftSection from './components/LeftSection.vue'
import Skills from './components/Skills.vue'
import AboutMe from './components/AboutMe.vue'

export default {
  name: 'App',
  components: {
    // Footer,
    Header,
    LeftSection,
    Skills,
    AboutMe
  }
}
</script>

<style>
  .app-container {
    display: grid;
    grid-template-columns: 3fr 1fr;
    grid-template-rows: auto auto 4fr auto;
    grid-template-areas: "h h" "e e" "l r" "f f";
    align-items: center;
    justify-items: center;
    /*background-color: #778ca3;*/
    font-family: 'Cabin', sans-serif;
  }

  .header {
    grid-area: h;
  }

  .about-me {
    grid-area: e;
  }

  .footer {
    grid-area: f;
  }

  .left-section {
    grid-area: l;
  }

  .skills {
    grid-area: r;
  }

@import url('https://fonts.googleapis.com/css2?family=Cabin:ital@1&display=swap');</style>
