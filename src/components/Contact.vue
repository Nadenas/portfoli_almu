<template>
  <div class="contact">
    <div class="contact-text">
      <div>
        <h2>Contacto</h2>
        <ul>
          <hr color="#5E5343" size="1px" />
          <li>Linkedin: <a href="https://www.linkedin.com/in/almudena-xico/">almudena-xico</a></li>
          <hr color="#5E5343" size="1px" />
          <li>Telefono: <a href="#">+34 647 07 55 40</a></li>
          <hr color="#5E5343" size="1px" />
          <li>Email: <a href="mailto: almudenaxico@gmail.com">almudenaxico@gmail.com</a></li>
          <hr color="#5E5343" size="1px" />
        </ul>
      </div>
      <img src="../assets/image/contact_me.jpg" width="800" height="800">
    </div>
    <div class="copyright-div">
      <p>
        Made with 💜 by Almudena De La Rosa &copy; {{ getYear() }}
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  methods: {
    getYear() {
      let today = new Date();
      let year = today.getFullYear();
      return year;
    },
  },
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .contact h2{
    font-family: Hatton;
    font-size: 50px;
    color: #5E5343;
    font-weight: 100;
    margin: 6rem 4rem;
  }
  .contact div,ul,li,a{
    text-decoration: none;
    color: #5E5343;
    font-size: 26px;
    list-style:none;
    padding: 1rem;
    font-weight: 100;
  }
  .contact div,ul,li{
    margin-left: 1rem;
    line-height: 5rem;
    color: #EA9E80;
    font-weight: bold;
  }
  a:hover{
    text-decoration: underline #5E5343;
  }
  .copyright-div{
    color:#5E5343;
    width: 100%;
  }
  p{
    font-size: 18px;
    text-align: center;
  }
  .contact-text{
    width: 100%;
    display: flex;
    justify-content: space-between;
  }
</style>