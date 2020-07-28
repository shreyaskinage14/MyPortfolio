<template>
  <div id="app">
    <Home />
    <About />
    <Portfolio />
    <Contact />
    <Footer />
    </div>
</template>

<script>
import Home from './components/home.vue'
import About from './components/about.vue'
import Portfolio from './components/portfolio.vue'
import Contact from './components/contact.vue'
import Footer from './components/footer.vue'
export default {
  name: 'App',
  components: {
    Home,
    About,
    Portfolio,
    Contact,
    Footer


  }
}
</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  }

body{
  background: #95A5A6;
}

.port{
  padding: 70px;
}

#home{
  height: 500px;
  width: 100%;
  background-image: url('./assets/coverimg.jpeg');
  font-family: 'Raleway', sans-serif;
}

.pp{
  float:right;
  font-family:'Poppins', sans-serif;
}

.pp1{
  display: inline-block;
}

.navdiv .pp .pp1 a{
  font-style: bold;
  font-size: 20px;
  margin-top: 20px;
  margin-right: 50px;
  width: 90px;
  height: 55px; 
  background: transparent;
  font-weight: bold;
  font-family: 'Raleway', sans-serif;
  opacity: 0.7;
}
.name{
  text-align: left;
  padding: 35px 0px 0px 70px;
  font-size: 30px;
  font-weight: lighter;

  font-family: 'Raleway', sans-serif;

}

.port{
  letter-spacing: 2px;
  font-weight: 1000;
  color: #616A6B;
  font-style: bold;
  margin: 65px 0px 0px 70px;
}

img{
  max-width: 100%;
  max-height: 100%;
  display: block;
  resize: 
}

nav{
  font-family:'Poppins', sans-serif;
  height: 95px;
}

.pp li a{
  text-decoration: none;
  color: #fff;
  font-family: Source Sans Pro;
  font-weight: lighter;
  font-size: 12px;
}

#aboutt{
  height: 100%;
  width: 100%;
  background:  #5DADE2;
  font-family: 'Raleway', sans-serif;

  padding-bottom: 10px;
}

#aboutt h1{
  padding-top: 20px;
  padding-left: 20px;
}

.paraabout{
  padding-left: 50px;
  text-align: left;
  display: flex;
}

p{
  text-align: left;
  font-size: 20px;
  font-style: normal;
}

#info{
  height: 400px;
  margin-bottom: 20px;
  background: black;
  font-family: 'Raleway', sans-serif;
}

#info h1{
  padding-top: 20px;
  padding-left: 20px;
}


#flex1{
    height: 500px;
    display: flex;
    flex-direction: row;
}


.flexc1{
  justify-content: space-between;
  margin:10px 40px;
}

.flexc2{
  height: 175px;
  width: 400px;
  margin-left: 150px;

}

.hobbies{
  height: 175px;
  width: 300px;
  margin-left: 170px; 
}

section{
  position: relative;
  justify-content: center;
  display: flex;
  align-items: center;
  min-height: 100vh;
  background: #112d42;
}

#contactt{
  position: relative;
  min-width: 750px;
  min-height: 450px;
  display: flex;
  z-index: 1000; 
}


.info{
  position: absolute;
  font-family: 'Raleway', sans-serif;
  width: 300px;
  height: 520px;
  background: #0f3959;
  z-index: 1;
  padding: 35px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  box-shadow: 0px 20px 20px rgba(0, 0, 0, 0.2);
}

.info .deta i{
  padding-right: 20px;

}

h2{
  color: #fff;
  font-size:24px;
  font-weight: 500;
}

.deta{
  position: relative;
  margin: 20px 0;
}

.deta li{
  position: relative;
  list-style: none;
  display: flex;
  margin: 0px 0px;
  padding: 40px 0px;
  cursor: pointer;
  align-items: flex-start;
}

span:nth-child(1){
  width: 30px;
  min-height: 30px;
}

span:nth-child(1) i{
  max-width: 100%;
  opacity: 0.5;
}

span:nth-child(2){
  color: #fff;
  margin-left: 10px;
  font-weight: 300;
  opacity: 0.5;
}

span:nth-child(2){
  max-width: 100%;
  opacity: 0.5;
}

li:hover span:nth-child(1) i,
li:hover span:nth-child(2){
  opacity: 1;
}

.sci{
  position: relative;
  display: flex;
  padding-left: 70px;
}

.sci li{
  list-style: none;
  margin-right: 15px;
}

.conform{
  position: relative;
  padding: 70px 0px 155px 100px;
  background: #21618C ;
  margin: 30px 0 0 300px;
  margin-left: 300px;
  margin-top: 30px;
  padding-left: 100px;
  width: 700px;
  height: 300px;
  box-shadow: 0 50px 50px rgba(0, 0, 0, 0.5);
  font-family: 'Raleway', sans-serif;
}

.conform h2{
  color: #0f3959;
  font-size: 32px;
  font-weight: 500;
  font-style: bold;
}

.forbox{
  position: relative;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  padding-top: 10px;
}

.inputbox{
  position: relative;
  margin: 0 0 10px 0;
}

.inputbox.w50{
  width: 47%;
  margin-bottom: 10px;
}

.inputbox.w100{
  width: 100%;
}

input,
textarea{
  width: 75%;
  padding: 10px 0px;
  resize: none;
  font-size: 18px;
  font-weight: 300;
  border: none;
  color: black ;
  background: #21618C ;  
  border-bottom: 2px solid #777;
  outline: none;
}
input{
    margin-bottom: 20px;
}
textarea{
  min-height: 70px;
  min-width: 50px;
}

span{
  position: absolute;
  left:0;
  padding: 5px 0;
  font-size: 18px;
  font-weight: 300;
  color: black;
  transition: 0.5s;
  pointer-events: none;
}

input:focus ~ span,
textarea:focus ~ span,
input:valid ~ span,
textarea:valid ~ span{
  transform: translateY(-30px);
  font-size: 18px;
  font-weight: 400;
  letter-spacing: 2px;
  color: red;
  opacity: 0;
}

input[type = "submit"]{
  position: relative;
  cursor: pointer;
  background: #0f3959;
  color: #fff;
  border: none;
  max-width: 150px;
  padding: 12px;
}

footer{
  background: black;
  width: 100%;
  height: 25px;
  padding-top: 5px;
  text-align: center;
}

.fa-facebook,
.fa-twitter,
.fa-instagram,
.fa-linkedin,
.fa-github{
  padding: 9px;
  font-size: 25px;
  text-align: center;
  letter-spacing: 3px;
  text-decoration: none;
  color: #fff;
}
.fa-map-o{
  color: #196F3D;
  box-shadow: none;
}

.fa-envelope-square{
  color: #E74C3C;
}

.fa-phone{
color: #27AE60;
}

.fa-map-o,
.fa-envelope-square,
.fa-phone{
  padding: 9px;
  font-size: 25px;
  text-align: left;
  text-decoration: none;
}

.fa:hover {
  opacity: 0.7;
  transform: translateY(-10px);
  transition: 0.2s;
}

.fa-facebook:hover {
  color: #3B5998;
  opacity: 0.7;
}

.fa-twitter:hover {
  color: #55ACEE;
  opacity: 0.7;
}

.fa-instagram:hover {
  color: #125688;
  opacity: 0.7;
}

.fa-linkedin:hover {
  color: #007bb5;
  opacity: 0.7;
}

.fa-github:hover {
  color: #007bb5;
  opacity: 0.7;
}
</style>
