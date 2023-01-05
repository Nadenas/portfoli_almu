<template>
  <div id="app">
    <div id="home" class="div-portfolio">
      <NavBar />
      <HelloWorld />
    </div>
    <div id="about" class="div-portfolio">
      <AboutMe />
    </div>
    <div id="projects" class="div-portfolio">
      <MyProyects />
    </div>
    <div id="contact" class="div-portfolio">
      <Contact />
    </div>
   </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavBar from './components/NavBar.vue'
import Contact from './components/Contact.vue'
import AboutMe from './components/AboutMe.vue'
import MyProyects from './components/MyProyects.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NavBar,
    Contact,
    AboutMe,
    MyProyects,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #EFE9E4;
  width: 100%;
}
@font-face {
  font-family: 'Hatton';
  src: url('./assets/fonts/PP Hatton Medium 500.otf') format('truetype');
  font-style: normal;
  font-weight: normal;
}
*{
  background-color: #EFE9E4;
  margin: 0;
}
.div-portfolio{
  width: 100%;
  height: 100vh;
}
</style>
