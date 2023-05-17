<template>
  <div class="home">
    <img alt="vue logo" class="car" src="@/assets/car.jpg"/>

    <div class="h1">
    </div>    
    <div class="header" >
    </div>
    
    <div class="title">
      <h2>Safe&Reliable Logistic Solution</h2>
    </div>
    <div class="Sub-title">
      <h3>KANGER Is An App Of Logistic Services For Drop Shipping Sector</h3>
    </div>
    <img alt="logo" class="logo" src="@/assets/logo.png"/>
  </div>

  <div class="menu">
  <input name="men" type="radio" id="home" class="tap" checked>
  <label for="home">Home</label>

  <input name="men" type="radio" id="About" class="tap">
  <RouterLink to="/About">
  <label for="About">About Us</label>
</RouterLink>
  <input name="men"  type="radio" id="Features" class="tap">
  <RouterLink to="/Features">
  <label for="Features">Features</label>
</RouterLink>
  <input name="men" type="radio" id="Services" class="tap">
  <RouterLink to="/Services">
  <label for="Services">Services</label>
  </RouterLink>
  <input name="men" type="radio" id="Partner" class="tap" >
  <RouterLink to="/Partner">
  <label for="Partner">Partner</label>
  </RouterLink>
  <input name="men" type="radio" id="Testimonials" class="tap" >
  <RouterLink to="/Testimonials">
  <label for="Testimonials">Testimonials</label>
  </RouterLink>

</div>
<div class="conteaner">
dir='rtl'
lang='ar'

<p dir="rtl" lang="ar" style="color:#000;font-size:15px; position: absolute; left:80em; top:0.5em;">اللغة العربية</p>
</div>
<button id="log-btn" >log in</button>

<div class="search-container">
<form class="box-search" action="#">
<input type="text" placeholder="Search.." name="search">
<textarea name="main" placeholder="Enter Your Order ID" id="textarea" class="form-control-search"></textarea>
</form>
</div>
<div class="track">
<button id="track" >Track</button></div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
  },
})
export default class HomeView extends Vue {}


</script>

<style>


.car{
left:0em;
top:0em;
position: absolute;
width: 100%;
height:100%;
}

a:link{
  text-decoration: none;
}

.header{
  position: absolute;
  left: -57.9vh;
  top: -13px;
  height:70px;
  width: 1910px;
  background: #fafafa;
opacity:99;

}

.h1{

position: absolute;
bottom:100;
background: rgba(0,0,0,0.5);
color:white;
width: 96.7%;
height: 94.5%;
top:0;
padding:20px;
}

.logo{
  position: absolute;
  top: 7px;
  left: 100px;
  width: 90px;
}

.menu{
  position:absolute;
  left:20em;
  padding: 8px;
  top: 6.5PX;
}

label{
 position: relative;
 color: #353535;
 font-family: 'Poppins';
 font-weight: bold;
 font-size: 16px;
 padding-bottom:  19px;
 padding-left: 19px;
 padding-top: 17px;
 padding-right: 10px;

}

input:checked +label{
  background-color: rgba(245, 172, 1, 1);
  color: #FAFAFA;
  
}
.tap{
  display:none;
}

#log-btn {
  box-sizing: border-box;
  position: absolute;
  width: 109px;
  height: 50px;
  left: 63.5em;
  background: rgba(245, 172, 1, 1);
  border-radius: 9.69444px;
  border: none;
  font-size: 20px;
  color: #FFFFFF;
top:3px;
}

.title{
  position: absolute;
  color: #fafafa;
  top: 250px;
  font-size:26.9px;
  left: 100px;
  width: 450px;
  font-family:'Poppins';

}

.Sub-title{
  position: absolute;
  color: #fafafa;
  top: 390px;
  font-size: 12px;
  left: 100px;
font-family:'Poppins';
}

.topnav-search-container {
  float: left;
  position: sticky;
  left: 15%;
  top: 20%;
}
.form-control-search {
  font-size: 17px;
  border: none;
  background-color: #ffffff;
  width: 420px;
  height: 50px;
  top: 430px;
  left: -500px;
  border-radius: 9.69444px;
  margin-right: 2%;
 
  box-sizing: border-box;
}

#textarea {
  position: relative;
  right: 5%;
 
}

.topnav input[type=text] {
  font-size: 18px;
  border: none;
  background-color: #061326;
  width: 300px;
  height: 40px;
  border-radius: 9.69444px;
  margin-right: 4%;
  top:-19px;
  box-sizing: border-box;
  left:2em;
}

#track{
  box-sizing: border-box;
  position: absolute;
  width: 109px;
  height: 50px;
  left: 27em;
  background: rgba(245, 172, 1, 1);
  border-radius: 9.69444px;
  border: none;
  font-size: 20px;
  color: #FFFFFF;
top:517px;

}




</style>