<template>
  <div class="proyects">
    <h2>Proyectos</h2>
    <div class="my-proyects">
        <div>
            <h5>
                <a href="https://github.com/Nadenas/proyecto-final-gym-hotel">Apptivate</a>
            </h5>
            <h6>Aplicaion pensada para hoteles con gimnasio</h6>
            <h6>React, Flask, Figma, Github</h6>
            <a href="https://github.com/Nadenas/proyecto-final-gym-hotel">
                <img src="../assets/image/apptivate.png" width="500" height="600">
            </a>
        </div>
        <div>
            <h5>
                <a href="#">Portfolio</a>
            </h5>
            <h6>Página personal donde muesto mi proyectos</h6>
            <h6>Vue, Github</h6>
            <a href="#">
                <img class="img-port" src="../assets/image/portfolio-almu.png" width="500" height="600">
            </a>
        </div>
        <div>
            <h5>
                <a href="https://github.com/Nadenas/React-TODO-application">To do list</a>
            </h5>
            <h6>Lista simples donde puede agregar nuevas tareas y eliminarlas</h6>
            <h6>React, Flask, Figma, Github</h6>
            <a href="https://github.com/Nadenas/React-TODO-application">
                <img src="../assets/image/todo-list.png" width="500" height="600">
            </a>
        </div>
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
    padding-top: .5em;
  }
  .my-proyects{
    display: flex;
    justify-content: space-around;
  }
  .proyects div, a{
    text-align: center;
    font-size: 26px;
    padding-top: .35rem;
    color: #5E5343;
    text-decoration: none;
  }
  h5{
    margin: 1.5em;
  }
  h6{
    line-height: 2em;
    font-weight: 100;
  }

  a img {
    margin-top: 1em;
	opacity: 1;
	-webkit-transition: .3s ease-in-out;
	transition: .3s ease-in-out;
  }
  a:hover img {
    opacity: .5;
  }
  .img-port{
    border: 1px solid #5E5343;
  }
</style>