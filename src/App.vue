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

    <section class="clients">
      <div class="client-img-container">
        <div class="client1">
          <img src="./assets/clients logo/fusebox.png" alt="client-images">
          <img src="./assets/clients logo/namtra.png" alt="client-images">
          <img src="./assets/clients logo/proximo.png" alt="client-images">
        </div>
        <div class="client2">
          <img src="./assets/clients logo/seotrust.png" alt="client-images">
          <img src="./assets/clients logo/wti.png" alt="client-images">
          <img src="./assets/clients logo/xponent21.png" alt="client-images">
        </div>
      </div>
    </section>

    <section class="testimonial">
      <h1>Testimonials</h1>
      <div class="testimonial-container">
        <div class="test">
          <div class="test-image">
            <img src="./assets/clientimg1.png" alt="client-image">
          </div>
          <div class="test-text">
            <p>I loved the experience at cardino. The whole process was seamless and the entire team made me feel so at home and of course they made an awesome website for my bakery. ALl the clients loved it and it helped get new customers.</p>
            <h3>John Doe</h3>
            <em>CEO Valid experts</em>
          </div>
        </div>
        <div class="test">
          <div class="test-image2">
            <img src="./assets/clientimg2.png" alt="client-image">
          </div>
          <div class="test-text">
            <p>I loved the experience at cardino. The whole process was seamless and the entire team made me feel so at home and of course they made an awesome website for my bakery. ALl the clients loved it and it helped get new customers.</p>
            <h3>Dan Rodgers</h3>
            <em>CEO Valid experts</em>
          </div>
        </div>
      </div>   
      <div class="test-button-group">
        <button></button>
        <img src="./assets/redarrow.png" alt="red-arrow">
      </div>
    </section>
    <section class="portfolio">
      <div class="portfolio-container">
        <h1>Portfolio</h1>
        <div class="portfolio-images">
          <img class="pf1" src="./assets/Rectangle 30.png" alt="portfolio">
          <img class="pf2" src="./assets/Rectangle 31.png" alt="portfolio"><br/>
          <img class="pf3" src="./assets/Rectangle 32.png" alt="portfolio">
        </div>
        <div class="portfolio-btn">
          <button>More Projects</button>
          <img src="./assets/bluearrow.png" alt="blue-arrow">
        </div>
      </div>
    </section>
    
    <footer>
        <div class="contact">
          <div class="contact-container">
              <h1>Contact Us</h1>
              <p>We'll love to get started with you right away, shoot us a mail to start discussing</p>
              <div class="contact-btn">
                <button>Get started</button>
                <img src="./assets/bluearrow.png" alt="blue-arrow">
              </div>
          </div>
        </div>
         <div class="bottom-nav">
            <ul class="fnav">
              <li>Home</li>
              <li>About</li>
              <li>Process</li>
              <li>Packages</li>
              <li>Testimonials</li>
              <li>Portfolio</li>
              <li>Team</li>
              <li>Contact</li>
            </ul>
            <ul class="fside-icons">
              <li><img src="./assets/icons/facebook.svg" alt="socials"></li>
              <li><img src="./assets/icons/instagram.svg" alt="socials"></li>
              <li><img src="./assets/icons/linkedin.svg" alt="socials"></li>
              <li><img src="./assets/icons/twitter.svg" alt="socials"></li>
            </ul>
          </div>
    </footer>
  </div>
</template>

<style scoped>
/* Bottom to Top Hierarchial Styling */

/* Footer */
.fnav{
  padding-left: 0px;
}
.bottom-nav{
  width: 80%;
  display: flex;
  justify-content: space-around;
  margin-top: 30px;
}
.bottom-nav ul{
  display: flex;
}
.bottom-nav li{
  list-style-type: none;
  margin: 12px;
}
.cta-img{
  height: 350px;
  width: 60%;
  position: absolute;
  z-index: -2;
}
.overlay{
  background-color: #0F101E;
  z-index: -1;
  height: 350px;
  width: 60%;
  position: absolute;
  opacity: 0.9;
}
footer{
  height: 600px;
  width: 100%;
  background-color: #252626;
  color: #fff;
  font-family: 'Roboto', sans-serif;
  font-size: 17px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.contact{
  width: 80%;
  height: 350px;
  color: #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  background:linear-gradient(0deg, rgba(15, 16, 30, 0.9), rgba(15, 16, 30, 0.9)), url("./assets/cta img.jpg");
  background-position: center;
  background-size: cover;
}
.contact-container{
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  width: 500px;
  text-align: center;
  z-index: 3;
}
.contact p{
  margin-top: 0px;
}
.contact-btn{
  width: fit-content;
  display: flex;
  justify-content: center;
  align-items: center;
}
.contact-btn img{
  position: relative;
  left: -25px;
  width: 60px;
}
.contact-btn button{
  padding: 12px;
  width: 150px;
  background-color: transparent;
  border: 1px solid red;
  font-size: 16px;
  color: #fff;
}
/* Portfolio */
.portfolio-btn{
  margin: auto;
  width: fit-content;
  display: flex;
  justify-content: center;
  align-items: center;
}
.portfolio-btn img{
  position: relative;
  left: -20px;
  width: 60px;
}
.portfolio-images img{
    height: 400px;
    margin: 20px;
}
.portfolio h1{
    margin: 20px;
}
.portfolio-btn button{
  padding: 12px;
  width: 150px;
  background-color: transparent;
  border: 1px solid #000;
  font-size: 16px;
}

.portfolio-container{
  margin: 15px 0px 15px 0px;
}

.portfolio{
  font-family: 'Roboto', sans-serif;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  font-size: 17px;
  width: 100%;
}

/* Testimonial */
.test-button-group{
  display: flex;
  align-items: center;
  margin-left: auto;
  margin-right: 20px;
}
.test-button-group button{
  width: 60px;
  height: 60px;
  background-color: transparent;
  border: 2px solid #fff;
}
.test-button-group img{
  position: relative;
  left: -30px;
}
.testimonial-container{
  margin-top: 40px;
  display: flex;
  justify-content: space-around;
  width: 100%;
}
.test-text p{
  border-bottom: 1px solid #fff;
  padding-bottom: 20px;
}
.test-text h3{
  margin: 5px;
}
.test{
  display: flex;
  flex-direction: row;
}
.test-image{
  background-color: red;
  height: 255px;
  width: 212px;
}
.test-image2{
  background-color: blue;
  height: 250px;
  width: 207px;
}
.test-image img{
  height: 250px;
  position: relative;
  left: -15px;
  top: 10px;
}
.test-image2 img{
  height: 230px;
  position: relative;
  left: -15px;
  top: 10px;
}
.test-text{
  width: 300px;
  margin-left: 20px;
}
.testimonial{
  background-color: #252626;
  color: #fff;
  font-family: 'Roboto', sans-serif;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  font-size: 17px;
  height: 600px;
  width: 100%;
}


/* Clients */
.clients{
  height: 500px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #65677c;
}

.clients img{
  padding: 30px;
  height: 70px;
}

.client1, .client2{
  border-bottom: 1px solid #afafaf;
  margin-bottom: 20px;
  display: flex;
  justify-content: space-around;
}


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
  font-size: 16px;
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
