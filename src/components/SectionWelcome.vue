<script>
    export default {
        name:"SectionWelcome"
    }
</script>


<template>
    <section class="welcome">

    <div class="title-text text-center container-xs">
      <h1>Welcome to Avada Healt</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi.</p>
      <p>exercitationem earum amet sint mollitia consectetur</p>
    </div>

    <!-- CARDS-SECTION-WELCOME -->
    <div class="cards container-small d-flex">

      <div class="card text-center">
        <img src="../assets/icon-1.png" alt="Appointment">
        <h3>SAME DAY APPOINTMENT</h3>
        <P>Lorem ipsum dolor sit amet, consectetur.</P>
        <P>Natus Lore ipsum dolor, consectetur .</P>
      </div>

      <div class="card text-center">
        <img src="../assets/icon-2.png" alt="Appointment">
        <h3>SAME DAY APPOINTMENT</h3>
        <P>Lorem ipsum dolor sit amet, consectetur.</P>
        <P>Natus Lore ipsum dolor, consectetur .</P>
      </div>

      <div class="card text-center">
        <img src="../assets/icon-3.png" alt="Appointment">
        <h3>SAME DAY APPOINTMENT</h3>
        <P>Lorem ipsum dolor sit amet, consectetur.</P>
        <P>Natus Lore ipsum dolor, consectetur .</P>
      </div>

      <div class="card text-center">
        <img src="../assets/icon-4.png" alt="Appointment">
        <h3>SAME DAY APPOINTMENT</h3>
        <P>Lorem ipsum dolor sit amet, consectetur.</P>
        <P>Natus Lore ipsum dolor, consectetur .</P>
      </div>

    </div>
    <!-- CARDS-SECTION-WELCOME -->

    
  </section>
  <!-- SEZIONE WELCOME -->
</template>



<style lang="scss" scoped>

.welcome{
  padding: 100px 0;
  background-color: #ffffff;
}

.title-text{
   color: var(--secondary-color);
   padding-bottom: 80px;
  h1{
    padding-bottom: 40px;
    font-size: 35px;
    font-weight: 300;
  }
  p{
    padding-bottom: 10px;
    font-weight: 200;
    font-size: 25px;
  }
}

.cards{
  width: 100%;
  padding: 0 10px;
  color: var(--secondary-color);
  .card{
    width: 25%;
    padding: 0 20px;
  }
  img{
    max-width: 100%;
  }

  h3{
    color: #45625f;
    font-weight: 200;
    font-size: 20px;
    padding: 15px 0;
  }
  p{
    color: #bcbcbd;
    font-size:13px ;
    padding: 10px 0;
  }
}

</style>