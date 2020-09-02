<template>
  <div id="app">
    <section class="landing">
      <div class="heading">
        <h2 class="logo">cardino web</h2>
        <ul class="nav">
          <li>Home</li>
          <li>About</li>
          <li>Process</li>
          <li>Packages</li>
          <li>Testimonials</li>
          <li>Portfolio</li>
          <li>Team</li>
          <li>Contact</li>
        </ul>
        <a href="#">Get Started</a>
      </div>
      <div class="side-icons">
        <img src="./assets/icons/facebook.svg" alt="socials">
        <img src="./assets/icons/instagram.svg" alt="socials">
        <img src="./assets/icons/linkedin.svg" alt="socials">
        <img src="./assets/icons/twitter.svg" alt="socials">
      </div>
    </section>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
.landing{
  height: 500px;
  width: 100%;
  background-color: #0F101E;
  color: #fff;
  font-family: 'Roboto', sans-serif;
}
.heading{
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.nav{
  display: flex;
}
.nav li{
  padding: 20px;
  list-style-type: none;
}
.heading a{
  text-decoration: none;
  padding: 6px;
  border-bottom: 1px solid #fff;
  color: #fff;
}
.side-icons{
  display: flex;
  flex-direction: column;
  width: fit-content;
  position: absolute;
  left: 0px;
  top: 150px;
}
.side-icons img{
  padding: 10px 0px 30px 20px;
}
.logo{
  padding-right: 25px;
  border-right: 3px solid royalblue;
}
</style>
