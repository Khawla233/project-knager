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


  <input name="men"  type="radio" id="Features" class="tap">
  <RouterLink to="Features">
  <label for="Features">Features</label>
  </RouterLink>

  <input name="men" type="radio" id="Services" class="tap" >
  <RouterLink to="Services">
  <label for="Services">Services</label>
  </RouterLink>

  <input name="men" type="radio" id="Partner" class="tap" >
  <RouterLink to="Partner">
  <label for="Partner">Partner</label>
  </RouterLink>

  <input name="men" type="radio" id="Testimonials" class="tap" checked>
  <label for="Testimonials">Testimonials</label>
  

</div>
<div class="conteaner">


<p dir="rtl" lang="ar" style="color:#000;font-size:15px; position: absolute; left:80em; top:0.5em;">اللغة العربية</p>
</div>
<button id="log-btn" >log in</button>

<div class=" text1">
Trstimonials
</div>

<div class="text22">
WHAT OUR CLIENT SAY
</div>


<img class="line" src="@/assets/Line.svg">

<img class="man" src="@/assets/man.svg">

<div class="t5">
Ali Ahmed
</div>

<div class="t6">
Fashion Company
</div>

<img class="white" src="@/assets/white.svg">

<div class="t7">
Always Listening, Always </div>

<div class="t8">
  Understanding </div>



  <button id="Send" >Send</button>

<div class="orange"></div>

<img class="logot" src="@/assets/logot.svg">

<div class="t9">
  An Electronic Platform Established In 2017 That  </div>

  <div class="t10">
Seeks To Be The First Platforms In Logistics Services</div>

<div class="t11">
And The Leader In Delivery And Freight Services </div>


<img class="mar" src="@/assets/mar.svg">

<div class="t12">
Lines Company For</div>

<div class="t13">
Programming And Marketing </div>

<div class="t14">
Tax Number 34564424525252 </div>

<div class="t15">
Quick Links </div>

<img class="sh1" src="@/assets/sh1.svg">
<img class="sh2" src="@/assets/sh2.svg">
<img class="sh3" src="@/assets/sh3.svg">
<img class="sh4" src="@/assets/sh4.svg">
<img class="sh5" src="@/assets/sh5.svg">

<div class="t16">
Terms And Conditions </div>
<div class="t17">
Privacy Of Use </div>
<div class="t18">
Return Policy </div>
<div class="t19">
Business Cooperation </div>
<div class="t20">
Developers Portal </div>


<div class="t21">
Get In Touch</div>

<img class="tele" src="@/assets/tele.svg">


<div class="t22">
+972595111957 </div>

<div class="t23">
+972595111957 </div>

<div class="t24">
Saudi Arabia, Dammam </div>

<img class="sms" src="@/assets/sms.svg">
<img class="loc" src="@/assets/loc.svg">

<img class="saudi" src="@/assets/saudi.svg">
<img class="stc" src="@/assets/stc.svg">
<img class="visa" src="@/assets/visa.svg">

<img class="e" src="@/assets/e.svg">
<img class="e1" src="@/assets/e1.svg">
<img class="e2" src="@/assets/e2.svg">

<img class="e3" src="@/assets/e3.svg">
<img class="e4" src="@/assets/e4.svg">
<img class="e5" src="@/assets/e5.svg">

<input type="text" class="text">

<Carousel :breakpoints="breakpoints">
      
      <Slide v-for="slide in 5" :key="slide">
      <p class="shm">  LOREM IPSUM DOLOR SIT AMET CONSECTETUR.IN NUNC MASSA NETUS QUIS NISI INTERDUM.PROIN MORBI BLANDIT NOV VEL SEMPER ENIM.
      </p>
      </Slide>
  
      <template #addons>
        <Navigation />
      </template>
  </Carousel>


</template>


<script lang="ts">
  
  import { defineComponent } from 'vue'
import { Carousel, Navigation, Slide } from 'vue3-carousel'

import 'vue3-carousel/dist/carousel.css'

export default defineComponent({
  name: 'BreakPoints',
  components: {
    Carousel,
    Slide,
    Navigation,
  },
  data: () => ({
    // carousel settings

    // breakpoints are mobile first
    // any settings not specified will fallback to the carousel settings
    breakpoints: {
      // 700px and up
      700: {
        itemsToShow: 2.5,
        snapAlign: 'center',
      },
      // 1024 and up
      1024: {
        itemsToShow: 1,
        snapAlign: 'start',
      },
    },
  }),
})
</script>

<style>
.shm {
  min-height: 200px;
  width: 30%;
  font-size: 16px;
  border-radius: 8px;
  display: flex;
  color: #535151;
text-align: left;
  align-items: left;
 margin-top:6em;
 margin-left: -52.7em;
 
 top:6em;
}

.carousel__slide {
  padding: 10px;
}

.carousel__prev{
 left:14em;
  border-radius: 8.5599px;
  background-color: #F5AC01;
  color:#FAFAFA;
  box-sizing: content-box;
  position: absolute;
  top:9em;
  width: 20px;
  height: 25px;
}
.carousel__next {
  box-sizing: content-box;
top:-10em;
width: 20px;
height: 25px;
position: absolute;
margin:570px;
right:13.4em;
  border-radius: 9.5559px;
  background-color: #F5AC01;
  color:#FAFAFA;
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
    color: rgba(135, 135, 135, 1);
    position: absolute;
    top:5em;
    left:6.6em; 
    font-size: 16px;
    font-family: 'Poppins';
    font-weight: lighter;
  }

  .text22{
    color: #000000;
    position: absolute;
   left:4em; 
   font-size: 25px;
   top:4.2em;
   font-weight: bold;
  }
  .line{
    position: absolute;
    top:9.3em;
    left:6.5em;
    width: 80px;
  }

  .t1{
position: absolute;
top: 15em;
font-size: 13px;
left: 8em;
color: rgba(137, 137, 137, 1);
font-family: Arial, Helvetica, sans-serif;

  }

  .t2{
position: absolute;
top: 16.7em;
font-size: 13px;
left: 8em;
color: rgba(137, 137, 137, 1);
font-family: Arial, Helvetica, sans-serif;

  }

  .t3{
position: absolute;
top: 18.4em;
font-size: 13px;
left: 8em;
color: rgba(137, 137, 137, 1);
font-family: Arial, Helvetica, sans-serif;

  }

  .t4{
position: absolute;
top: 20em;
font-size: 13px;
left: 8em;
color: rgba(137, 137, 137, 1);
font-family: Arial, Helvetica, sans-serif;

  }

  .man{
    position: absolute;
    top: 19.5em;
    width: 64px;
    left: 6.5em;
  }

  .t5{
    position: absolute;
    top: 20em;
    left: 11em;
  }

  .t6{
    position: absolute;
    top: 21.5em;
    left: 11em;
    color: rgba(137, 137, 137, 1);
  }

  .white{
    position: absolute;
    width: 425px;
    left: 50em;
    top: 6em;

  }
  .text{
position: absolute;
width: 250px;
height: 17%;
border: white;
left: 66em;
top: 17em;
background:white;
}

  .t7{
    position: absolute;
    top: 6.5em;
    left: 36.5em;
font-size: x-large;
color:rgba(53, 53, 53, 1);

  }

  .t8{
    position: absolute;
    top: 7.7em;
    left: 36.5em;
font-size: x-large;
color:rgba(53, 53, 53, 1);

  }


  .W{
    position: absolute;
    width: 280px;
    left: 54.7em;
    top: 14.2em;
  }

  #Send {
  box-sizing: border-box;
  position: absolute;
  width: 277px;
  height: 50px;
  left: 44em;
  background: rgba(245, 172, 1, 1);
  border-radius: 9.69444px;
  border: none;
  font-size: 20px;
  color: #FFFFFF;
top:19.5em;
}

.orange{
  top: 30em;
  position: absolute;
  left: 0em;
  width: 1481px;
  height: 265px;
  background-color: rgba(245, 172, 1, 1);
}


.logot{
  top: 31.5em;
  position: absolute;
  left: 6em;
  width: 90px;
}


.t9{
  top: 36.3em;
  position: absolute;
  left: 6em;
  color: #FAFAFA;
}

.t10{
  top: 37.5em;
  position: absolute;
  left: 6em;
  color: #FAFAFA;
}

.t11{
  top: 38.7em;
  position: absolute;
  left: 6em;
  color: #FAFAFA;
}

.mar{
  top: 41.2em;
  position: absolute;
  left: 6em;
  width: 90px;
}

.t12{
  top: 48.7em;
  position: absolute;
  left: 14.7em;
  color: #FAFAFA;
  font-size: 13.5px;
}

.t13{
  top: 50em;
  font-size: 13.5px;
  position: absolute;
  left: 14.6em;
  color: #FAFAFA;
}

.t14{
  top: 52.3em;
  font-size: 13.5px;
  position: absolute;
  left: 7em;
  color: #FAFAFA;
}

.t15{
  top: 24.7em;
  font-size: 20px;
  position: absolute;
  left: 34em;
  color: #FAFAFA;
}

.sh1{
  top: 33em;
  position: absolute;
  left: 42.5em;
  width: 10px;
}

.sh2{
  top: 35.5em;
  position: absolute;
  left: 42.5em;
  width: 10px;
}

.sh3{
  top: 38.5em;
  position: absolute;
  left: 42.5em;
  width: 10px;
}

.sh4{
  top: 41.4em;
  position: absolute;
  left: 42.5em;
  width: 10px;
}

.sh5{
  top: 44em;
  position: absolute;
  left: 42.5em;
  width: 10px;
}



.t16{
  top: 37.6em;
  font-size: 14px;
  position: absolute;
  left: 50em;
  color: #FAFAFA;
}

.t17{
  top: 40.4em;
  font-size: 14px;
  position: absolute;
  left: 50em;
  color: #FAFAFA;
}

.t18{
  top: 43.9em;
  font-size: 14px;
  position: absolute;
  left: 50em;
  color: #FAFAFA;
}

.t19{
  top: 47.2em;
  font-size: 14px;
  position: absolute;
  left: 50em;
  color: #FAFAFA;
}

.t20{
  top: 50.1em;
  font-size: 14px;
  position: absolute;
  left: 50em;
  color: #FAFAFA;
}

.tele{
  top: 38em;
  font-size: 14px;
  position: absolute;
  left: 75.8em;
}

.t21{
  top: 24.6em;
  font-size: 20px;
  position: absolute;
  left: 53em;
  color: #FAFAFA;
}

.t22{
  top: 38.4em;
  font-size: 14px;
  position: absolute;
  left: 78em;
  color: #FAFAFA;
}

.t23{
  top: 41em;
  font-size: 14px;
  position: absolute;
  left: 78em;
  color: #FAFAFA;
}
.t24{
  top: 43.6em;
  font-size: 14px;
  position: absolute;
  left: 78em;
  color: #FAFAFA;
}

.sms{
  top: 41em;
  font-size: 14px;
  position: absolute;
  left: 75.8em;
}

.loc{
  top: 43.4em;
  font-size: 14px;
  position: absolute;
  left: 75.8em;
}

.saudi{
  top: 46em;
  font-size: 14px;
  position: absolute;
  left: 76em;

}

.stc{
  top: 46em;
  font-size: 14px;
  position: absolute;
  left: 82.5em;
}

.visa{
  top: 46em;
  font-size: 14px;
  position: absolute;
  left: 86.3em;
}


.e{
  top: 49em;
  font-size: 14px;
  position: absolute;
  left: 85.5em;
}

.e1{
  top: 49em;
  font-size: 14px;
  position: absolute;
  left: 81em;
}
.e2{
  top: 49em;
  font-size: 14px;
  position: absolute;
  left: 76.5em;
}




.e3{
  top: 49.7em;
  font-size: 14px;
  position: absolute;
  left: 86.2em;
}

.e4{
  top: 49.7em;
  font-size: 14px;
  position: absolute;
  left: 81.7em;
}
.e5{
  top: 49.8em;
  font-size: 14px;
  position: absolute;
  left: 77.2em;
}
</style>