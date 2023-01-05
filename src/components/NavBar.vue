<template>
  <div class="nav_bar">
    <ul>
        <li><a href="#home">INICIO</a></li>
        <li><a href="#about">SOBRE MI</a></li>
        <li><a href="#projects">PROYECTOS</a></li>
        <li><a href="#contact">CONTACTO</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .nav_bar ul li{
    display: inline;
    font-family: 'Roboto', sans-serif;
    font-size: 20px;
    font-weight: bold;
    color: #5E5343;
    padding-left: 5rem;
    margin-right: 5rem;
  }
  a{
    margin: 0 -.35rem;
    padding: .25rem .35rem;
    text-decoration: none;
    color: #5E5343;
  }
  a:hover{
    text-decoration: underline #5E5343;
  }
  .nav_bar ul{
    text-align: center;
    padding: 3rem 0;
  }
  .nav_bar{
    width: 100%;
    display: contents;
  }
</style>