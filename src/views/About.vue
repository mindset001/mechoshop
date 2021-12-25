<template>
  <div >
   
  <div>
  <Navbar/>
    <div class="hero">
    <h1>About Our Company</h1>
    
    </div>
    <div class="second">
        <h4 style="color:#dfb871;">All About Us</h4>    
        <h2 style="color:#000;">  WHO WE ARE</h2>
        <p>
            We are a group of technology enthusiasts who are really passionate about making financial inclusion count
        </p>

    </div>

          <div class="third">
            <div class="right">
            <div class="mission">
            <h1>Our Mission</h1>
              Everyday, we strive to understand our customers and leverage technoloy, data and innovation to deliver outstanding service experiences.
            
            </div>
            <div class="vision">
            <h1>Our Vision</h1>
            <p>We are Nigeria's most convenient company delivering outstanding service experience</p>
            
            </div>
            
            </div>

            <div class="left">
            <img src="../assets/about-us.jpg" alt="">
            </div>
          </div>

          <!-- <div class="fourth">
          <img src="../assets/experience.png" alt="">
          <div class="text">
            <h1>25 Years of Experience</h1>
            <h2>in Car Maintenance Business</h2>
            <p>Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic
             life One day however a small line of blind text by the name of Lorem Ipsum decided to leave for the far World of Grammar..</p>
          </div>

          
          </div> -->
  </div>
  <Working/>
   <Product/>
    <Footer/>

  </div>
</template>


<script>
import Navbar from '@/components/Navbar.vue'
import Product from '@/components/Product.vue';
import Footer from '@/components/Footer.vue'
import Working from '@/components/Working.vue'

export default {
    components:{
        Navbar,
        Product,
        Footer,
        Working
    }
    
}
</script>

<style scoped>

  .hero{
    background: black;
    display: flex;
    height: 300px;
    color: #dfb871;
    justify-content: center;
    align-items: center;
    
  }
  .second{
    display: flex;
    flex-direction: column;
    height: 300px;
    justify-content: center;
    align-items: center;
  }
  .third{
    display: flex;
    padding-left: 20em;
    padding-right: 20em;
  }
   .fourth{
    display: flex;
    padding-left: 20em;
    padding-right: 20em;
    background: #dfb871;
  }

  .text{
    color: #fff;
    padding-top: 80px;
  }

</style>

