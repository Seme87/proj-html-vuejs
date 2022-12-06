<script>


export default {
  name: 'AppHeader',
  data(){
    return {
      links: [
        {
          href:"#",
          label:"HOME",
          active: false,
        },
        {
          href:"#",
          label:"ABOUT",
          active: true,
        },
        {
          href:"#",
          label:"DEPARTMENTS",
          active: false,
        },
        {
          href:"#",
          label:"ARTICLES",
          active: false,
        },

      ],
    };
  },
  methods: {
    changeLink(index) {
      
      this.links.forEach((elm, i) => {
        console.log(i)
        if(i === index) {
          elm.active = true;
          console.log(elm.active)
        }else {
          elm.active = false;
        }
      });
    },
  },
  
};
</script>

<template>
    <header>
      <div class="header-top container d-flex">
        <div class="logo">
          <img src="../assets/medical_logo_1x_light.png" alt="">
        </div>
        <nav class="main-nav">
          <ul class="d-flex align-items-center">
            <li v-for="(item, index) in links">
              <a :href="item.href" @click.prevent="changeLink(index)"  :class="{ active: item.active }" >{{item.label}}</a>
            </li>
            
            <li><button class="btn">MAKE APPOINTMENT</button></li>
          </ul>
        </nav>
      </div>
      <div class="header-bottom container-small">
        <div class="title">
          <h1>Caring <span>For life</span></h1>
        </div>
        <p>Kind Words can be short and easy to speak, but their echoes are truly endless.Avada Health focuses on you as if it was our own family</p>
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
  justify-content: space-between;
  align-items: center;
  padding: 25px 0;
  
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
    
  }
}

a{
   text-decoration: none;
    color: white;
  }

.active{
  color:var(--primary-color);
}

.header-bottom{
  color: white;
  
  padding: 200px 0;
  h1{
    font-size: 80px;
    font-weight: 300;
    span{
      color:var(--primary-color);
    }
  }
  p{
    display: inline-block;
    font-size: 25px;
    padding-bottom: 50px ;
    padding-top: 30px;
  }

  .btn{
    background-color: var(--primary-color);
    border: none;
    color: white;
  }
}
</style>
