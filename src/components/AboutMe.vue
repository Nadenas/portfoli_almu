<template>
  <div class="proyects">
    <h2>Sobre mí</h2>
    <div class="my-proyects">
        <h5>Formada en <a href="https://4geeksacademy.com/es/inicio">4Geeks Academy Spain</a>, sigo aprendiendo sobre todas las nuevas tecnologías que encuentro desafiantes.</h5>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .proyects h2{
    font-family: Hatton;
    font-size: 50px;
    color: #5E5343;
    font-weight: 100;
    text-align: center;
    margin-top: 1em;
  }
  .my-proyects{
    display: flex;
    justify-content: space-around;
  }
  .proyects div{
    text-align: center;
    font-size: 26px;
    padding-top: .35rem;
    color: #5E5343;
    margin-top: 5em;
  }
  a{
    color: #EA9E80;
    font-weight: 100;
    text-decoration: none;
  }
</style>