<script>
export default {
  name: 'AppFooter',
  data(){
    return {
      info: [
        {
          href:"#",
          field:"Cardiology",
        },
        {
          href:"#",
          field:"Pediatrics",
        },
        {
          href:"#",
          field:"Diabetes Care",
        },
        {
          href:"#",
          field:"Pre-natal Care",
        },
        {
          href:"#",
          field:"Ultrasound Echocardiogram",
        },
       
      ]
    }
  }
}
</script>

<template>

  <footer >

    <!-- FOOTER TOP -->
    <div class="container d-flex">

      <!-- PRIMA COLONNA -->
      <div class="col">

        <div class="logo">
          <img src="../assets/medical_logo_1x_dark.png" alt="">
        </div>

        <div class="text-logo">
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit sit amet consectetur adipisici</p>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit sit amet consectetur adipisici elit</p>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit sit amet consectetur adipisici</p>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing </p>
        </div>
      
        <h4 class="about-us">LEARN ABOUT US</h4>

        <div class="icon">
          <a href="#"><i class="facebook fa-brands fa-square-facebook"></i></a>
          <a href="#"><i class="twitter fa-brands fa-square-twitter"></i></a>
          <a href="#"><i class=" youtube fa-brands fa-youtube"></i></a>
          <a href="#"><i class="instagram fa-brands fa-square-instagram"></i></a>
        </div>
  
      </div>
      <!-- PRIMA COLONNA -->


      <!-- SECONDA COLONNA -->
      <div class="col">
        <div class="info">
          <h3>CONTACT INFORMATION</h3>
          <div class="decoration"></div>
          <div class=" position">
            <i class="fa-solid fa-location-dot"></i><span>121 King Street</span>
          </div>
          <div class="contact">
            <i class="fa-solid fa-phone"></i><span>1-000089997</span>
          </div>
        </div>
      </div>
      <!-- SECONDA COLONNA -->


      <!-- TERZA COLONNA -->
      <div class="col">

        <div class="info">
          <h3>MEDICAL DEPARTMENTS</h3>
          <div class="decoration"></div>
        </div>

        <nav class="footer-nav">
          <ul>
            <li v-for="item in info">
              <a :href="info.href"><i class="fa-solid fa-circle-chevron-right"></i>{{ item.field }}</a>
            </li>
            
          </ul>
        </nav>

        <button class="btn">VIEW OUR DEPARTMENTS</button>
          
      </div>
      <!-- TERZA COLONNA -->


    </div>
    <!-- FOOTER TOP -->



    <!-- FOOTER BOTTOM -->
    <div class="footer-bottom">
        <div class="content container d-flex ">
          <div class="copyrights ">
            <p>&#169; Copyrights | Avada by Team by team fusion | All rights reserved | Powered by Wordpress</p>
            <div class="chevron">
              <i class="fa-solid fa-angle-up"></i>
            </div>
          </div>
        </div>
    </div>
    <!-- FOOTER BOTTOM -->


  </footer>

</template>

<style lang="scss" scoped>


footer{
  background-color: #ffff;
  padding-top: 75px;
  
}



.col{
  width: calc(100% / 3);
  padding-right: 30px;
}

.text-logo{
  padding-top: 20px ;
  margin-bottom: 10px;
  border-bottom: 1px solid #777777 ;
  p{
    font-size: 13px;
    padding-bottom: 20px;
    color: #777777;

  }
}

.about-us{
  font-size: 15px;
  font-weight: 400;
  color: #333c4e;
  margin-bottom: 30px;
}

.info{
  color:#333c4e;
  font-size: 15px;
  font-weight: 100;
  
  .decoration{
    margin-top: 30px;
    margin-bottom: 25px;
    height: 2px;
    width: 10%;
    background-color:#3aafbf ;
  }
}

.icon{
  margin-bottom: 100px;
}

.position{
  margin-bottom: 20px;
}

.contact, .position{
  color: #3aafbf;
  span{
    padding-left: 5px;
    color: #777777;
  }
}

ul li a{
  text-decoration: none;
  color: #777777;
  font-size: 15px;
  
  i{
    color: #3aafbf;
    font-size: 20px;
    padding-right: 5px;
  }
}

ul{
  list-style: none;
  li{
    padding-bottom: 10px;
  }
}

.btn{
  font-size:15px ;
  margin-top: 40px;
  background-color: transparent;

}

.footer-bottom{
  // padding:25px 0;
  background-color: #f7f7f7;
  position: relative;
}



.content{
  position: relative;
}

.copyrights {
  padding: 25px 0;
}


.chevron{
  position: absolute;
  right: 0;
  bottom:0;
  height: 35px;
  width: 45px;
  color: #ffff;
  background-color:#474747 ;
  display: flex;
  justify-content: center;
  align-items: center;
}

</style>
