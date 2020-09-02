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

      <div class="landing-text">
        <h1>cardino</h1>
        <p>Web Agency</p>
      </div>

      <div class="landing-image-group">
          <img src="./assets/Group1.png" alt="Landing-image">
          <img class="lig2" src="./assets/Group 2.png" alt="Landing-image">
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

<style scoped>
.landing-image-group{
    position: absolute;
    top: 150px;
    left: 630px;
}
.landing-image-group img{
  height: 400px;
  margin-right: 20px;
}
.lig2{
  margin-top: 30px;
  position: absolute;
}
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
  border-right: 2px solid royalblue;
}
.landing-text{
   width: fit-content;
   margin: 50px auto 50px 350px;
   z-index: 2;
   position: absolute;
}
.landing-text h1{
  font-size: 120px;
  margin: 0;
  font-weight: bold;
}
.landing-text p{
  font-size: 40px;
  font-weight: bold;
  margin: 0;
  background-image: linear-gradient(royalblue, royalblue);
  background-position: 0% 100%;
  background-repeat: no-repeat;
  background-size: 60% 15px;
}
</style>
