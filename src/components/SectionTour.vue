<script>
    export default {
        name:"SectionTour"
    }
</script>


<template>
    <section class="tour d-flex align-items-center">

        <div class="s-meet-top container-xs text-center">

            <div class="logo d-flex justify-content-center">
                <img src="../assets/icon-6.png" alt="Logo Meet-doctor">
            </div>

            <h2>HOUR HEALT SERVICES</h2>
            <div class="decoration d-flex justify-content-center">
                <div></div>
            </div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit corporis</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing.</p>

            <div class="logo-play d-flex justify-content-center">
                <img src="../assets/play-icon.png" alt="Logo Meet-doctor">
            </div>

        </div>

    </section>
</template>



<style lang="scss" scoped>
.tour{
    padding: 165px 0;
    background-image: url(../assets/paralax-bg-tour-facilities.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}

.s-meet-top{
    color: #ffff;
    
    img{
        max-width: 100%;
        display: block;
    }
    h2{
        font-weight: 200;
        padding-top: 25px;
        font-weight: 200;
        font-size: 35px;
    }

    p{
        padding: 10px 0;
        font-size:20px ;
        font-weight: 100;
        color: #ffff;
    }
} 

.decoration{
    padding:40px 0 ;
    div{
        height: 2px;
        width: 230px;
        background-color: #ffff;
    }
}

.logo-play{
    padding-top: 35px;
    img{
        height: 60px;
        width: 60px;
    }
}


</style>