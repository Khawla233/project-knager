<template>
            <div class="back"></div>

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


  <input name="men"  type="radio" id="Features" class="tap">
  <RouterLink to="Features">
  <label for="Features">Features</label>
  </RouterLink>

  <input name="men" type="radio" id="Services" class="tap" checked>
  
  <label for="Services">Services</label>
  

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
    Services
</div>

<div class="text22">
  MULTIPLE JOBS AND MORE
</div>
<img class="line" src="@/assets/line2.svg">

<img alt="S1" class="S1" src="@/assets/S1.svg">
<div class="rest">
    Restaurants
</div>

<img alt="D2" class="D2" src="@/assets/D2.svg">
<img alt="S2" class="S2" src="@/assets/S2.svg">

<div class="ship">
    Shipping Companies
</div>

<img alt="S3" class="S3" src="@/assets/S3.svg">
<div class="gov">
    Government Facilities
</div>


<img alt="D4" class="D4" src="@/assets/D4.svg">
<img alt="S4" class="S4" src="@/assets/S4.svg">

<div class="sc">
Scheduling
</div>

<img alt="D5" class="D5" src="@/assets/D5.svg">
<img alt="S5" class="S5" src="@/assets/S5.svg">

<div class="bak">
Bakeries And Sweets 
</div>

<img alt="D6" class="D6" src="@/assets/D6.svg">
<img alt="S6" class="S6" src="@/assets/S6.svg">

<div class="com">
    Commercial Facilities
</div>

<img alt="D7" class="D7" src="@/assets/D7.svg">
<img alt="S7" class="S7" src="@/assets/S7.svg">

<div class="food">
Food 
</div>

<img alt="D8" class="D8" src="@/assets/D8.svg">
<img alt="S8" class="S8" src="@/assets/S8.svg">

<div class="pub">
Publishing Companies
</div>

<img alt="D9" class="D9" src="@/assets/D9.svg">
<img alt="S9" class="S9" src="@/assets/S9.svg">

<div class="pro">
Productive Families
</div>


<img alt="D10" class="D10" src="@/assets/D10.svg">
<img alt="S10" class="S10" src="@/assets/S10.svg">

<div class="eco">
Ecommerce
</div>

<img alt="D11" class="D11" src="@/assets/D11.svg">
<img alt="S11" class="S11" src="@/assets/S11.svg">

<div class="tra">
Transprtation
</div>

<img alt="D12" class="D12" src="@/assets/D12.svg">
<img alt="S12" class="S12" src="@/assets/S12.svg">

<div class="mob">
Mobile Application
</div>

</template>
<style>
.back{
    background-color: #F5AC01;
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0em;
    left: 0em;
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
    color: rgb(255, 255, 255);
    position: absolute;
    top:10.5em;
    left:5em; 
    font-size: 19px;
    font-family: 'Poppins';
    font-weight: lighter;
  }

  .text22{
    color: #ffffff;
    position: absolute;
   left:3.1em; 
   font-size: 30px;
   top:8.2em;
   font-weight: bold;
  }

  .line{
    position: absolute;
    top:19em;
    left:6em;
    width: 80px;
  }

  .S1{
    position: absolute;
    top: 22em;
    left: 6em;

  }

  .rest{
    position: absolute;
    top: 16.5em;
    left: 7.5em;
    color: #FAFAFA;
    font-size: 22px;
  }

  .D2{
    position: absolute;
    top: 22em;
    left: 6em;
  }

  .S2{
    position: absolute;
    top: 22em;
    left: 22em;
  }

  .ship{
    position: absolute;
    top: 16.5em;
    left: 19em;
    color: #FAFAFA;
    font-size: 22px;
  }

  .S3{
    position: absolute;
    top: 22em;
    left: 41em;
  }
  .gov{
    position: absolute;
    top: 16.5em;
    left: 33em;
    color: #FAFAFA;
    font-size: 22px;
  }
.D4{
    position: absolute;
    top: 28em;
    left: 6em;
}

.S4{
    position: absolute;
    top: 28.8em;
    left: 6.7em;
}

.sc{
    position: absolute;
    top: 21em;
    left: 7.5em;
    color: #FAFAFA;
    font-size: 22px;
}

.D5{
    position: absolute;
    top: 28em;
    left: 22em;
}

.S5{
    position: absolute;
    top: 28.5em;
    left: 22.8em;
}

.bak{
    position: absolute;
    top: 21em;
    left: 19em;
    color: #FAFAFA;
    font-size: 22px;
}

.D6{
    position: absolute;
    top: 28em;
    left: 41em;
}

.S6{
    position: absolute;
    top: 28.8em;
    left: 41.6em;
}

.com{
    position: absolute;
    top: 21em;
    left: 33em;
    color: #FAFAFA;
    font-size: 22px;
}

.D7{
    position: absolute;
    top: 34em;
    left: 6em;
}

.S7{
    position: absolute;
    top: 34.7em;
    left: 6.7em;
}

.food{
    position: absolute;
    top: 25.4em;
    left: 7.5em;
    color: #FAFAFA;
    font-size: 22px;
}


.D8{
    position: absolute;
    top: 34em;
    left: 22em;
}

.S8{
    position: absolute;
    top: 34.8em;
    left: 23em;
}

.pub{
    position: absolute;
    top: 25.3em;
    left: 19em;
    color: #FAFAFA;
    font-size: 22px;
}


.D9{
    position: absolute;
    top: 34em;
    left: 41em;
}

.S9{
    position: absolute;
    top: 34.6em;
    left: 41.8em;
}

.pro{
    position: absolute;
    top: 25.3em;
    left: 33em;
    color: #FAFAFA;
    font-size: 22px;
}

.D10{
    position: absolute;
    top:40em;
    left: 6em;
}

.S10{
    position: absolute;
    top: 40.9em;
    left: 6.8em;
}

.eco{
    position: absolute;
    top: 29.7em;
    left: 7.5em;
    color: #FAFAFA;
    font-size: 22px;
}


.D11{
    position: absolute;
    top: 40em;
    left: 22em;
}

.S11{
    position: absolute;
    top: 40.8em;
    left: 22.8em;
}

.tra{
    position: absolute;
    top: 29.7em;
    left: 19em;
    color: #FAFAFA;
    font-size: 22px;
}


.D12{
    position: absolute;
    top: 40em;
    left: 41em;
}

.S12{
    position: absolute;
    top: 40.8em;
    left: 41.8em;
}

.mob{
    position: absolute;
    top: 29.7em;
    left: 33em;
    color: #FAFAFA;
    font-size: 22px;
}

</style>