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

  <input name="men" type="radio" id="Partner" class="tap" checked>
  <label for="Partner">Partner</label>
  
  <input name="men" type="radio" id="Testimonials" class="tap">
  <RouterLink to="/Testimonials">
  <label for="Testimonials">Testimonials</label>
  </RouterLink>

</div>
<div class="conteaner">


<p dir="rtl" lang="ar" style="color:#000;font-size:15px; position: absolute; left:80em; top:0.5em;">اللغة العربية</p>
</div>
<button id="log-btn" >log in</button>



<div class="text22">
OUR AWESOME PARTNER 
</div>
<img class="line" src="@/assets/Line.svg">



<img class="line5" src="@/assets/line5.svg">
<img class="line55" src="@/assets/line55.svg">

<div class="text">
DO YOU WANT TO INCREASE YOUR INCOME BY JOINING KNAGER ?
</div>
<img class="star" src="@/assets/star.svg">
<img class="star2" src="@/assets/star2.svg">
<img class="star3" src="@/assets/star3.svg">
<img class="star4" src="@/assets/star4.svg">
<img class="star5" src="@/assets/star5.svg">
<img class="star6" src="@/assets/star6.svg">
<img class="star7" src="@/assets/star7.svg">


<div class="t1">
    Unlimited Reception Of Requests
</div>

<div class="t2">
 Requests From Stores And Individuals
</div>

<div class="t3">
Sort As Per Your Wish Accurate Delivery Confirmation
</div>

<div class="t4">
Rewarding Profits For Each Request
</div>

<div class="t5">
Arrived The Order With Your Car Or Bike
</div>

<div class="t6">
  Branch Delivery Support
</div>

<div class="t7">
100% Advance Payment
</div>

<img class="google" src="@/assets/google.svg">
<img class="apple" src="@/assets/apple.svg">


<img alt="ph" class="ph" src="@/assets/ph.svg">
<img alt="ph3" class="ph3" src="@/assets/ph3.svg">
<img alt="ph2" class="ph2" src="@/assets/ph2.svg">


<img class="black2" src="@/assets/black2.svg">
<img class="black" src="@/assets/black.svg">

<div class="R">
LINK YOUR ONLINE STORE OR FACILTIES NOW WITH KNAGER
</div>

<div class="R1">
AND ADD EXPRESS DELIVERY SERVICE TO THE GROWTH AND DEVELOPMENT OF YOUR BUSINESS 
</div>

<button id="order" >Order A Caption Now</button>


<Carousel :breakpoints="breakpoints">
      
      <Slide v-for="slide in 10" :key="slide">
        <img class="carousel__item" src="@/assets/K1.svg" >
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
        itemsToShow: 5,
        snapAlign: 'start',
      },
    },
  }),
})
</script>
<style>

.carousel__item {
  height: 200px;
  width: 200px;
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 20px;

  }

.carousel__slide {
  padding: 40px;
}

.carousel__prev,
.carousel__next {
  box-sizing: content-box;
top:-13.3em;
margin: 688px;
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



  .text22{
    color: #000000;
    position: absolute;
   left:4em; 
   font-size: 25px;
   top: 3.7em;
   font-weight: bold;
  }

  .line{
    position: absolute;
    top:8.3em;
    left:6.5em;
    width: 80px;
  }

.K1{
position: absolute;
left: 18em;
width: 150px;
height: 150px;
top: 180px;
}
.K2{
position: absolute;
left:30em;
width: 150px;
height: 150px;
top: 180px;
}

.K3{
position: absolute;
left: 42em;
width: 150px;
height: 150px;
top: 180px;
}

.K4{
position: absolute;
left: 54em;
width: 150px;
height: 150px;
top: 180px;
}
.K5{
position: absolute;
left: 66em;
width: 150px;
height: 150px;
top: 180px;
}

.line5{
    position: absolute;
    top: 355px;
    width: 420px;
    left: 250px;
}
.line55{
    position: absolute;
    top: 355px;
    width: 420px;
    left: 805px;
}

.text{
    color: #000000;
    position: absolute;
   left:50em; 
   font-size: 16px;
   top:24em;
   font-weight: bold;
  }

  .star{
    position: absolute;
    top: 26em;
    width: 20px;
    left: 50em;
  }

  .star2{
    position: absolute;
    top: 28em;
    width: 20px;
    left: 50em;
  }
  .star3{
    position: absolute;
    top: 30em;
    width: 20px;
    left: 50em;
  }
  .star4{
    position: absolute;
    top: 32em;
    width: 20px;
    left: 50em;
  }
  .star5{
    position: absolute;
    top: 34em;
    width: 20px;
    left: 50em;
  }
  .star6{
    position: absolute;
    top: 36em;
    width: 20px;
    left: 50em;
  }
  .star7{
    position: absolute;
    top: 38em;
    width: 20px;
    left: 50em;
  }

  .t1{
    position: absolute;
    top: 26em;
    left: 52em;
    color: rgba(104, 104, 104, 1);
  }

  .t2{
    position: absolute;
    top: 28em;
    left: 52em;
    color: rgba(104, 104, 104, 1);
  }

  .t3{
    position: absolute;
    top: 30em;
    left: 52em;
    color: rgba(104, 104, 104, 1);
  }

  .t4{
    position: absolute;
    top: 32em;
    left: 52em;
    color: rgba(104, 104, 104, 1);
  }

  .t5{
    position: absolute;
    top: 34em;
    left: 52em;
    color: rgba(104, 104, 104, 1);
  }

  .t6{
    position: absolute;
    top: 36em;
    left: 52em;
    color: rgba(104, 104, 104, 1);
  }

  .t7{
    position: absolute;
    top: 38em;
    left: 52em;
    color: rgba(104, 104, 104, 1);
  }

  .google{
    position: absolute;
    top: 41em;
    left: 51em;
    width: 180px;
    border-radius: 9.69444px;

  }

  .apple{
    position: absolute;
    top: 41em;
    left: 64.5em;
    border-radius: 9.69444px;
    width: 180px;
  }


.ph{
width: 410px;
position: absolute;
left: 15.8em;
top: 25em;

}

.ph3{
width: 250px;
position: absolute;
left: 20.8em;
top: 23em;

}

.ph2{
width: 218px;
position: absolute;
left:21.8em;
top: 24.6em;
border-radius: 9.69444px;

}

.black2{
  position: absolute;
  top: 56em;
  width: 1465px;
  left: 0em;
}

.black{
  position: absolute;
  top: 56em;
  width: 1465px;
  left: 0em;
}

.R{
  position: absolute;
  top: 48em;
color: #FAFAFA;  
left: 20em;
font-size: 20px;
}

.R1{
  position: absolute;
  top: 68em;
color: #FAFAFA;  
left: 23em;
font-size: 15px;
}

#order {
  box-sizing: border-box;
  position: absolute;
  width: 220px;
  height: 50px;
  left: 33em;
  background: rgba(245, 172, 1, 1);
  border-radius: 9.69444px;
  border: none;
  font-size: 18px;
  color: #FFFFFF;
top:60em;
}
</style>

