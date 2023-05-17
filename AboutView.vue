<template>
  <img alt="rip" class="rip" src="@/assets/rip.svg">
    <div class="header" >
  
  
  </div>


  <img alt="logo" class="logo" src="@/assets/logo.png">
  <div class="menu">
  <input name="men" type="radio" id="home" class="tap">
  <RouterLink to="/main">
  <label for="home">Home</label>
</RouterLink>

  <input name="men" type="radio" id="About" class="tap"   checked>

  <label for="About">About Us</label>

  <input name="men"  type="radio" id="Features" class="tap">
  <RouterLink to="/Features">
  <label for="Features">Features</label>
</RouterLink>
  <input name="men" type="radio" id="Services" class="tap">
  <RouterLink to="/Services">
  <label for="Services">Services</label>
  </RouterLink>
  <input name="men" type="radio" id="Partner" class="tap">
  <RouterLink to="/Partner">
  <label for="Partner">Partner</label>
  </RouterLink>
  <input name="men" type="radio" id="Testimonials" class="tap">
  <RouterLink to="/Testimonials">
  <label for="Testimonials">Testimonials</label>
  </RouterLink>

</div>
<div class="conteaner">


<p dir="rtl" lang="ar" style="color:#000;font-size:15px; position: absolute; left:80em; top:0.5em;">اللغة العربية</p>
</div>
<button id="log-btn" >log in</button>

<img alt="box" class="box" src="@/assets/box.svg">

<div class=" text1">
  About Us
</div>

<div class="text22">
  WE ARE KNAGER
</div>
<img class="line" src="@/assets/Line.svg">

<div class="text3">
    An Electronic Platform Established in 2017
    That Seeks To Be The First Platform in
     Logistics Services And The Leader In Delivery
     And Freight Services Through A Wide
     Network Of Companies And Individuals And
     A Fleet Of Drivers Available Around The 
     Clock Throughout The Region
</div>

</template>
<style>
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

.rip{
position: absolute;
width:100%;
height:1100PX;
top: -14.7em;
left: 0em;
overflow: hidden;
}

.box{
position: absolute;
left:440px;
top: 160px;
}

.text1{
    color: #ffffff;
    position: absolute;
    top:10em;
    left:25.5em; 
    font-size: 19px;
    font-family: 'Poppins';
    font-weight: lighter;
  }

  .text22{
    color: #FFFFFF;
    position: absolute;
   left:19.5em; 
   font-size: 25px;
   top:9em;
   font-weight: bold;
  }

  .line{
    position: absolute;
    top:17em;
    left:30.5em;
    width: 80px;
  }

  .text3{
    position: absolute;
    top:22em;
    color: #FFFFFF;
    width: 400px;
    font-size: 16px;
    left:31em;
    text-align: left;
    padding-top: 2px;
    font-weight: lighter;
    line-height: 35px;
    word-spacing:2px;
}
</style>