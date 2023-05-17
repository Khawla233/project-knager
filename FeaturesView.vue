<template>
    <div class="header" >
  
  </div>
  <img alt="logo" class="logo" src="@/assets/logo.png">
  <div class="menu">
  <input name="men" type="radio" id="home" class="tap">
  <RouterLink to="/main">
  <label for="home">Home</label>
</RouterLink>

  <input name="men" type="radio" id="About" class="tap"   >
<RouterLink to="/About">
  <label for="About">About Us</label>
</RouterLink>


  <input name="men"  type="radio" id="Features" class="tap" checked>
  <label for="Features">Features</label>

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


<div class=" text1">
    Features
</div>

<div class="text22">
  WHY CHOOSE US
</div>
<img class="line" src="@/assets/Line.svg">


<div class="box1">
<img class="F1" src="@/assets/F1.svg">

<div class="textbx1">
    INSIDE AND OUT SIDE THE <br>
    REGION

    <div class="box1tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
  
</div>
</div>
<div class="box2">

<img class="F2"  src="@/assets/F2.svg">
<div class="textbox2">
  ALL KINDS OF PRODUCT
</div>

<div class="box2tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
</div>
<div class="box3"> 
  <img class="F3"  src="@/assets/F5.svg">
<div class="textbox3">
  FULL COVERAGE
</div>

<div class="box3tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
</div>
<div class="box4"> 
  <img class="F4"  src="@/assets/F3.svg">
<div class="textbox4">
  DELIVERY IN LESS AN HOUR
</div>

<div class="box4tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
</div>
<div class="box5">
  <img class="F5"  src="@/assets/F4.svg">
<div class="textbox5">
  DOOR PICKUP
</div>

<div class="box5tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
    </div>
   </div>
<div class="box6">
  <img class="F6"  src="@/assets/F6.svg">
<div class="textbox6">
 ONLINE PAMENT
</div>

<div class="box6tex">
        LOREM IPSUM DOLOR SIT AMET CONSECTETUR.<br>
        FUSCE.LOREM IPSUM DOLOR SIT AMET<br>
        CONSECTETUR. FUSCE.
 </div>
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

.text1{
    color: rgba(135, 135, 135, 1);
    position: absolute;
    top:9.5em;
    left:5em; 
    font-size: 19px;
    font-family: 'Poppins';
    font-weight: lighter;
  }

  .text22{
    color: #000000;
    position: absolute;
   left:3.8em; 
   font-size: 25px;
   top:9em;
   font-weight: bold;
  }

  .line{
    position: absolute;
    top:17em;
    left:6em;
    width: 80px;
  }

  .box1{

position: absolute;
top: 19em;
width: 370px;
height: 180px;
left:6em;
background: #F9F9F9;
}

.box2{

position: absolute;
top: 19em;
width: 370px;
height: 180px;
left:31em;
background: #F9F9F9;
}

.box3{

position: absolute;
top: 19em;

width: 370px;
height: 180px;
left:56em;
background: #F9F9F9;
}

.box4{

position: absolute;
top: 32em;
width: 370px;
height: 180px;
left:6em;
background: #F9F9F9;
}


.box5{

position: absolute;
top: 32em;
width: 370px;
height: 180px;
left:31em;
background: #F9F9F9;
}

.box6{

position: absolute;
top: 32em;
width: 370px;
height: 180px;
left:56em;
background: #F9F9F9;
}


.F1{
background-color:#F9F9F9 ;
top:1.4em;
left:2em;
height: 60px;
position: absolute;
}




.textbx1{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box1tex{
text-align: left; 
position: absolute;
color: #878787;
top:  6em;
left:0em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}



.F2{
position: absolute;
color:#F5AC01;
font-size: 40px;
left:0.5em;
top:0.5em;
height: 70px;
}

.textbox2{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box2tex{
text-align: left; 
position: absolute;
color: #878787;
top:  9.6em;
left:11em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}



.F3{
position: absolute;
color:#F5AC01;
font-size: 40px;
left:0.5em;
top:0.5em;
height: 70px;
}

.textbox3{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box3tex{
text-align: left; 
position: absolute;
color: #878787;
top:  9.6em;
left:11em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}


.F4{
 position: absolute;
color:#F5AC01;
font-size: 40px;
left:0.5em;
top:0.5em;
height: 70px;
}

.textbox4{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box4tex{
text-align: left; 
position: absolute;
color: #878787;
top:  9.6em;
left:11em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}


.F5{
position: absolute;
color:#F5AC01;
font-size: 40px;
left:0.5em;
top:0.5em;
height: 70px;
}

.textbox5{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box5tex{
text-align: left; 
position: absolute;
color: #878787;
top:  9.6em;
left:11em;
width: 300px;
font-size: 10px;
font-weight: lighter;
}


.F6{
position: absolute;
color:#F5AC01;
font-size: 40px;
left:0.5em;
top:0.5em;
height: 70px;
}

.textbox6{
color: #F5AC01;
position: absolute;
top:2.3em;
font-weight: bold;
text-align: left;
left:7em;
}

.box6tex{
text-align: left; 
position: absolute;
color: #878787;
top:  9.6em;
left:11em;
width: 300px;
font-size: 10px;
font-weight:lighter;
}


</style>