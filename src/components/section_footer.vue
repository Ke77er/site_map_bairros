<template>
    <section class="footer-section">
      <div class="footer">
        <div class="social">
          <a href="#header"><i class="fas fa-leaf logo"></i></a>
          <ul>
            <li>
              <a href="https://twitter.com/ancientnutr" target="_blank"><i class="fab fa-twitter-square"></i></a>
            </li>
            <li>
              <a href="https://www.instagram.com/explore/tags/modernsuperfood/" target="_blank"><i class="fab fa-instagram"></i></a>
            </li>
            <li>
              <a href="https://www.facebook.com/ancientnutrition/" target="_blank"><i class="fab fa-facebook-square"></i></a>
            </li>
          </ul>
        </div>
        <div class="footer-links">
          <h4>Links</h4>
          <ul>
            <li>
              <a href="#benefits">Benefits</a>
            </li>
            <li>
              <a href="#products">Products</a>
            </li>
            <li>
              <a href="#demo-video">Video</a>
            </li>
            <li>
              <a href="#shopping-cart">Cart</a>
            </li>
          </ul>
        </div>
        <div class="email-signup">
          <h4>Subscribe</h4>
          <form id="form" action="https://www.freecodecamp.com/email-submit">
            <label>Sign up and stay up-to-date with new <br>products, tips, news and recepies.</label><br>
            <div class="section-wrapper">
              <input id="email" type="email" name="email" placeholder="Enter email..." required>
              <input id="submit" class="btn-ghost" type="submit" value="Sign up">
            </div>
          </form> 
        </div>
      </div>
     <p class="footer-credit">Copyright © 2018 Designed by Gelso Designs. All rights reserved. Website content taken from <a href="http://ancientnutrition.com/" target="_blank">Ancient Nutrition</a>.</p>
    </section>
</template>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="vendors/js/jquery.waypoints.min.js"></script>
<script>
export default {
  name: "SectionFooter",
  data() {
    return {
    };
  },
  computed: {
  },
  mounted() {
  },
  methods: {
  },
};
</script>
<style>
@import url('../src/assets/styles.css');
</style>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Lato:300,400');
@import url('https://use.fontawesome.com/releases/v5.0.13/css/all.css');

/* ---------- Colors ----------*/
/* Orange: #E67E22 */
/* Dark (hover) orange: #D67118 */
/* Light gray: #F9FAFC */
/* Dark blue: #222651 */

/* -------------------------------------------*/
/* BASIC SETUP */
/* -------------------------------------------*/

.clearfix {zoom: 1}
.clearfix:after {
    content: '.';
    clear: both;
    display: block;
    height: 0;
    visibility: hidden;
}

/* -------------------------------------------*/
/* REUSABLE */
/* -------------------------------------------*/
.logo {
	font-size: 40px;
	width: auto;
	color: #E67E22;
}

h1 {
	font-size: 55px;
	font-weight: 300;
	padding-top: 260px;
  padding-bottom: 4%;
	word-spacing: 4px;
	line-height: 1.6;
	text-align: center;
  margin: 0 auto;
}

h3 {
	font-size: 38px;
	font-weight: 200;
	text-align: center;
	padding-top: 80px;
	margin: 0;
}

h4 {
	font-size: 20px;
	font-weight: 200;
}

p {
	font-size: 20px;
	color: #555;
}

.btn {
	color: #FFF;
	background-color: #E67E22;
	border: none;
  border-radius: 200px;
	padding: 15px 30px;
	font-size: 18px;
	font-weight: 200;
}

.btn a {
	text-decoration: none;
	color: #FFF;
}

.btn:hover {
	color: #FFF;
	background-color: #D67118;
}

.btn-ghost {
	margin: 12px auto 6px auto;
	text-align: center;
	font-weight: 200;
	font-size: 16px;
	width: 160px;
	padding: 6px 12px;
  border-radius: 200px;
	border: 2px solid #E67E22;
	color: #E67E22;
	background-color: #FFF;
}

.btn-ghost:hover {
	font-weight: 200px;
	border: 2px solid #D67118;
	color: #FFF;
	background-color: #D67118;
}

.container {
	display: flex;
	flex-wrap: wrap;
	max-width: 1140px;
	margin: 60px auto 80px auto;
}

/* -------------------------------------------*/
/* HEADER */
/* -------------------------------------------*/
#nav-bar {
	width: 100%;
	position: fixed;
	z-index: 9999;
	background-color: #FFF;
	box-shadow: 1px 1px 2px #ccc;
}

#nav-bar div {
	max-width: 1140px;
	margin: 0 auto;
}

#nav-bar .logo {
	float: left;
	margin: 12px auto;
}

.main-nav {
	list-style: none;
	float: right;
	margin: 21px auto;
  padding-left: 0;
}

.main-nav li {
	display: inline-block;
	padding-left: 15px;
	font-size: 19px;
	font-weight: 200;
}

.main-nav li:nth-child(4) {	word-spacing: 4px; }

.main-nav li a {
	text-decoration: none;
	color: #555;
}

.main-nav li a:hover {
	text-decoration: none;
	padding-bottom: 5px;
	border-bottom: 2px solid #D67118;
}

.mobile-nav-icon { display: none; }

/* ---------- HERO SECTION ----------*/
.hero-container {
	max-width: 1140px;
	margin: 0 auto;
    display: flex;
/*    min-height: 100vh;*/
    height: 700px;
}

.hero-container .outer-div { margin: 0 auto; }

.hero-container img {
	width: 455px;
 	height: auto;
/*	padding-top: 35%;*/
	padding-top: 120px;
}

.hero-container .btn {
  display: block;
	margin: 0 auto;
}

/* -------------------------------------------*/
/* BENEFITS SECTION */
/* -------------------------------------------*/
.benefits-section {
	background-color: #222651;
	margin-top: 0;
	margin-bottom: 0;
}

.benefits-section h3 { color: #FFF; }

.container .outer-div {	margin: 0 auto; }

 .container .benefit-listing {
	display: inline-block;
 	background-color: #222651;
	border: 2px solid #E67E22;
	width: 200px;
	height: 200px;
	border-radius: 200px;
	margin: 0 10px;
}

.container div p {
	line-height: 1.6;
	text-align: center;
	margin: auto;
	padding-top: 8%;
	width: 150px;
	color: #fff;
}

.container div span {
	font-size: 35px;
	color: #E67E22;
	padding-left: 20px;
}

/* -------------------------------------------*/
/* PRODUCTS SECTION */
/* -------------------------------------------*/
.container .product-listing {
  display: inline-block;
	max-width: 200px;
	height: auto;
	margin: 0 10px;
}

.product-listing img {
  width: 200px;
	height: auto;
}

.product-listing h4 {
	text-align: center;
	margin: 2px auto;
	font-weight: 300;
	font-size: 18px;
	padding-bottom: 10px;
}

.product-listing h4 span {
	font-weight: 400;
	font-size: 18px;
	color: #555;
	padding-left: 0;
}

.btn-ghost { display: block; }

/* -------------------------------------------*/
/* VIDEO SECTION */
/* -------------------------------------------*/
.video-section {
	background-color: #222651;
	margin-top: 0;
	margin-bottom: 0;
}

.video-section h3 { color: #FFF; }

.video-section div ul {
	width: 470px;
	height: auto;
	margin: 0;
  color: #FFF;
}

.video-section div li {
	font-size: 18px;
	font-weight: 200;
	padding-bottom: 15px;
}

/* -------------------------------------------*/
/* FOOTER SECTION */
/* -------------------------------------------*/
.footer-section {
	max-width: 1140px;
	margin: 0 auto;
	background-color: #FFF;
 	padding-top: 80px;
  padding-bottom: 20px;
} 

.footer {
    display: flex;
    flex-wrap: wrap;
    margin: 0 auto;
}

.footer div { margin: 0 auto; }

.footer .logo { color: #E67E22; }

.footer h4 {
    margin-top: 0;
    margin-bottom: 15px;
    font-weight: 300;
}

.footer ul {
    list-style: none;
    text-decoration: none;
    padding-left: 0;
}

.social { float: left; }

.social ul li { float: left; }

.social ul i {
    font-size: 30px;
    color: #555;
    padding-top: 10px;
    padding-right: 10px;
    text-align: center;  
}

.social ul i:hover { color: #D67118; }

.footer-links ul a {
    list-style: none;
    text-decoration: none;
    color: #555;
    font-size: 17px; 
    line-height: 1.5;
}

.footer-links ul a:hover { color: #D67118; }

.email-signup { padding-bottom: 40px; }

.footer-section form {
	text-align: left;
  font-size: 17px;
  line-height: 1.5;
}

.section-wrapper {
  min-width: 224px;
  overflow: hidden;
  display: inline-block;
  padding-top: 10px;
}

input[type=email], select, textarea {
	width: 165px;
	padding: 8px;
	padding-left: 20px;
	border: 1px solid #E67E22;
	border-radius: 200px 0 0 200px;
	box-sizing: border-box;
	margin-top: 4px;
	margin-bottom: 4px;
	resize: vertical;
	font-size: 13px;
  float: left;
}

.footer-section .btn-ghost {
	color: #FFF;
	background-color: #E67E22;
  margin: 4px 0 4px 0px;
  border-radius: 0 200px 200px 0;
  width: 100px;
}

.footer-section .btn-ghost:hover {
	color: #FFF;
	border: 2px solid #D67118;
	background-color: #D67118;
}

.footer-credit {
  font-size: 16px;
  text-align: center;
	margin: 0 auto;
	padding-top: 20px;
  padding-right: 2%;
  padding-left: 2%;
	border-top: 2px solid #D67118;
}

.footer-credit a { color: #E67E22; }

.footer-credit a:hover,
.footer-credit a:active {
  color: #D67118;
}

/* -------------------------------------------*/
/* MEDIA QUERIES */
/* -------------------------------------------*/
@media only screen and (max-width:1180px){
  #nav-bar .logo { margin-left: 20px; }
    
  .mobile-nav-icon {
    margin-right: 20px;
    padding-right: 0px;
  }
    
  #nav-bar .main-nav { margin-right: 20px; }
    
  .video-section .container {
    padding-right: 2%;
    padding-left: 2%;
  }
    
  .video-section .demo-listing { padding-bottom: 15px; }
}

@media only screen and (max-width:1060px) {
  h1 {
    padding-top: 250px;
    padding-right: 2%;
    font-size: 50px;
  }
    
  .hero-container img { width: 400px; }
    
  .benefits-section .container { margin-bottom: 50px; }
    
  .benefits-section .container .outer-div { padding-bottom: 30px; }
    
  .products-section .container { margin-bottom: 40px; }
    
  .products-section .container .outer-div { padding-bottom: 40px; }
    
  .video-section .container { margin-bottom: 65px; }
    
  .video-section div ul { max-width: 460px; }
}

@media only screen and (max-width:815px) {
  .hero-container { max-height: 600px; }
    
  h1 {
    padding-top: 220px;
    font-size: 40px;
  }
    
  .hero-container img { width: 350px; }
}

@media only screen and (max-width:725px) {
  .mobile-nav-icon {
    margin-right: 20px;
    padding-right: 0px;
  }
    
  .hero-container img { display: none; }
    
  .hero-container {
		background-image: linear-gradient(rgba(255, 255, 255, 0.85), rgba(255, 255, 255, 0.85)), url(https://www.stack3d.com/wp-content/uploads/2017/07/organic-bone-broth-protein.jpg);
		background-position: right;
		background-size: cover;
    max-height: 500px;
  }
    
  h1 {
    padding-top: 180px;
    padding-left: 2%;
    font-weight: 300;
    font-size: 45px;
  } 
    
  h3 {
    padding-right: 2%;
    padding-left: 2%;
  }
    
  .social {
    padding-left: 2%;
    padding-right: 30px;
  }
    
  .footer-links { padding-right: 30px; }
    
  .email-signup { padding-right: 2%; }
}

@media only screen and (max-width:600px) {
  .hero-container { min-height: 450px; }
    
  h1 {
    padding-top: 190px;
    font-size: 40px;
  } 
    
  h3 { font-size: 32px; }
    
  #video {
    width: 330px;
    height: 180px;
    padding-right: 2%;
    padding-left: 2%;
  }
    
  .video-section div ul { width: 320px; }
    
  .video-section div ul li {
    width: 300px;
    font-size: 17px;
  }
}
    
@media only screen and (max-width:524px) {
	.mobile-nav-icon {
		display: block;
		font-size: 25px;
		text-align: right;
		padding-top: 15px;
	}
	
	#nav-bar .main-nav {
		margin-right: 0;
		padding-right: 0;
		margin-bottom: 0;
		padding-bottom: 0;
	}
	
  .main-nav { 
    display: none; 
    position: absolute;
    width: 100%;
    right: 0;
    top: 32px;
    background-color: #FFF;
    padding-top: 5px;
    padding-bottom: 10px;
    padding-right: 15px;
    text-align: center;
    box-shadow: 0 3px 2px -2px rgba(214, 113, 24, 0.3);
  }

  .main-nav li {
    font-size: 19px;
    display: block;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 0;
    background-color: #FFF;
    margin: 0 auto;
  }

  .main-nav li:hover a {
    text-decoration: none;
    padding-bottom: 5px;
    margin: 0 auto;
    color: #FFF;
  }

  .main-nav li:hover { background-color: #D67118; }    
}

@media only screen and (max-width:400px) {
  .hero-container { min-height: 400px; }

  h1 {
    padding-top: 200px;
    font-size: 35px;
  }    
}
</style>