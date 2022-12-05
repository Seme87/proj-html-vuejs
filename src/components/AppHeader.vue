<script>


export default {
  name: 'AppHeader',
  
}
</script>

<template>
    <header>
      <div class="header-top container d-flex">
        <div class="logo">
          <img src="../assets/medical_logo_1x_light.png" alt="">
        </div>
        <nav class="main-nav">
          <ul class="d-flex align-items-center">
            <li><a href="">HOME</a></li>
            <li><a href="">ABOUT</a></li>
            <li><a href="">DEPARTMENTS</a></li>
            <li><a href="">ARTICLES</a></li>
            <li><button class="btn">MAKE APPOINTMENT</button></li>
          </ul>
        </nav>
      </div>
      <div class="header-bottom container-small">
        <div class="title">
          <h1>Caring <span>For life</span></h1>
        </div>
        <p>Kind Words can be short and easy to speak,but their echoes are truly endless.Avada Health focuses on you as if it was our own family</p>
        <button class="btn">LEARN MORE</button>

      </div>
    </header>
</template>

<style lang="scss" scoped>

header{
  background-image: url(../assets/header-image-homepage.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.header-top{
  background-color: antiquewhite;
  justify-content: space-between;
  align-items: center;
  padding: 50px 0;
  
}
.logo img{
  max-width: 100%;
}

.main-nav{
  
  .btn{
    background-color: var(--primary-color);
    border: none;
    color: white;
  }
  li{
    padding: 0 10px;
    list-style: none;
    a{
      text-decoration: none;
      color: white;
    }
  }
}

.header-bottom{
  color: white;
  background-color: navy;
  padding: 400px 0;
  h1{
    font-size: 100px;
    font-weight: 400;
    span{
      color:var(--primary-color);
    }
  }
}
</style>
