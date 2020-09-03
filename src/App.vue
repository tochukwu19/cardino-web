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

    <section class="about">
      <div class="content">
        <h1>About Us</h1>
        <p>We are a team of skilled HTML experts who specialize in turning your psd designs into well are usable code for your company We are a team of skilled HTML experts who specialize in turning your psd designs</p>
        <button>View Team</button>
        <img src="./assets/redarrow.png" alt="red-arrow">
      </div>
      <div class="xter-container">
        <div class="xter">
          <img src="./assets/icons/bulb.svg" alt="ideas">
          <p>We get your awesome ideas and immediately start coming up with functional ways to make them work</p>
        </div>
        <div class="xter">
          <img src="./assets/icons/spanner.svg" alt="ideas">
          <p>We get your awesome ideas and immediately start coming up with functional ways to make them work</p>
        </div>
        <div class="xter">
          <img src="./assets/icons/html5.svg" alt="ideas">
          <p>We get your awesome ideas and immediately start coming up with functional ways to make them work</p>
        </div>
        <div class="xter">
          <img src="./assets/icons/smilingface.svg" alt="ideas">
          <p>We get your awesome ideas and immediately start coming up with functional ways to make them work</p>
          </div>
      </div>
    </section>

    <section class="why">
      <div class="why-container">
        <div class="why-text">
          <h1>Why us?</h1>
          <p>We are a team of skilled HTML experts who specialize in turning your psd designs into well are usable code for your company We are a team of skilled HTML experts who specialize in turning your psd designs</p>
        </div>
        <div class="why-img-container">
          <img class="why1" src="./assets/Group 15.png" alt="why-images">
          <img class="why2" src="./assets/Group 16.png" alt="why-images">
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
/* Bottom to Top Hierarchial Styling */

/* Why section */
.why-text{
  width: 400px;
  z-index: 5;
}
.why-text h1{
  font-size: 50px;
}
.why-img-container{
    position: relative;
    left: -150px;
}
.why1{
  height: 400px;
  margin-right: -138px;
}
.why2{
  height: 300px;
}
.why{
  height: 500px;
  width: 100%;
  background-color: #0F101E;
  color: #fff;
  font-family: 'Roboto', sans-serif;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 17px;
}
.why-container{
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-around;
  margin-left: 90px;
}

/* about section */
.about{
  height: 100vh;
  width: 100%;
  font-family: 'Roboto', sans-serif;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.content{
  width: 300px;
}
.content h1{
  font-weight: bold;
  font-size: 30px;
}
.content button{
  padding: 12px;
  width: 150px;
  background-color: transparent;
  border: 1px solid #000;
  font-size: 14px;
}
.content img{
  position: relative;
  left: -30px;
}
.xter-container{
  display: flex;
  width: 500px;
  flex-wrap: wrap;
  justify-content: space-around;
}
.xter{
  width: 200px;
  margin-bottom: 10px;
  margin-right: 20px;
}

/* Landing section */
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
