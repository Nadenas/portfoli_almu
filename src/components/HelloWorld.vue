<template>
  <div class="home_style">
    <div class="img_style">
      <img src="../assets/image/almu_img.jpg">
    </div>
    <div class="home_info">
      <h1>Almudena <br/> De La Rosa</h1>
      <h5>FULL STACK</h5>
      <span>Soy desarrolladora web. Mi especialidad es <b>Vue y django</b>.</span>
    </div>
    <a href="https://github.com/Nadenas">
      <img src="../assets/image/icon-github.png" width="50" height="50">
    </a>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .home_style{
    margin-top: 3em;
    display: flex;
    justify-content: center;
  }
  .img_style img{
    border-radius: 50%;
    border: 1px solid #5E5343;
    width: 650px;
    margin-top: 3em;
  }
  .home_info h1{
    font-family: Hatton;
    font-size: 100px;
    font-weight: 100;
    margin-left: 12rem;
    color: #5E5343;
    margin-top: 12rem;
  }
  .home_info h5{
    font-family: 'Roboto', sans-serif;
    font-weight: 900;
    font-size: 20px;
    margin-left: 12rem;
    color: #5E5343;
  }
  .home_info span{
    font-family: 'Roboto', sans-serif;
    font-weight: 300;
    font-size: 20px;
    margin-left: 12rem;
    color: #5E5343;
  }
  a{
    align-self: flex-end;
  }
  b{
    color: #EA9E80
  }
</style>
