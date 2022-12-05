<script>
    export default {
        name: "SectionHealthService"
        
    }
</script>


<template>

    <section class="health">
        <!-- SEZIONE SUPERIORE HEALTH -->
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
        </div>
        <!-- SEZIONE SUPERIORE HEALTH -->

        <!-- SEZIONE INFERIORE HEALTH CARDS -->
        <div class="cards d-flex container-small">

            <div class="card text-center">
                <img src="../assets/icon-11.png" alt="icon 11">
                <h4>REHABILITATION CENTER</h4>
                <P>Lorem ipsum dolor sit amet, consectetur adipisicing</P>
                <P>Lorem ipsum dolor sit amet, consectetur</P>
                <P>Lorem ipsum dolor sit amet</P>
            </div>

            <div class="card text-center">
                <img src="../assets/icon-12.png" alt="icon 11">
                <h4>DENTAL IMPLANTS</h4>
                <P>Lorem ipsum dolor sit amet, consectetur adipisicing</P>
                <P>Lorem ipsum dolor sit amet, consectetur</P>
                <P>Lorem ipsum dolor sit amet</P>
            </div>

            <div class="card text-center">
                <img src="../assets/icon-13.png" alt="icon 11">
                <h4>MEDICINE RESERCH</h4>
                <P>Lorem ipsum dolor sit amet, consectetur adipisicing</P>
                <P>Lorem ipsum dolor sit amet, consectetur</P>
                <P>Lorem ipsum dolor sit amet</P>
            </div>

            <div class="card text-center">
                <img src="../assets/icon-14.png" alt="icon 11">
                <h4>BLOOD BANK</h4>
                <P>Lorem ipsum dolor sit amet, consectetur adipisicing</P>
                <P>Lorem ipsum dolor sit amet, consectetur</P>
                <P>Lorem ipsum dolor sit amet</P>
            </div>

            <div class="card text-center">
                <img src="../assets/icon-15.png" alt="icon 11">
                <h4>PHARMACEUTICAL ADVICE</h4>
                <P>Lorem ipsum dolor sit amet, consectetur adipisicing</P>
                <P>Lorem ipsum dolor sit amet, consectetur</P>
                <P>Lorem ipsum dolor sit amet</P>
            </div>

            <div class="card text-center">
                <img src="../assets/icon-16.png" alt="icon 11">
                <h4>MEDICAL COUNSELING</h4>
                <P>Lorem ipsum dolor sit amet, consectetur adipisicing</P>
                <P>Lorem ipsum dolor sit amet, consectetur</P>
                <P>Lorem ipsum dolor sit amet</P>
            </div>

        </div>
        <!-- SEZIONE INFERIORE HEALTH CARDS -->


    </section>

</template>



<style lang="scss" scoped>
 .health{
    padding-top: 115px;
    padding-bottom: 135px;
 }
.s-meet-top{
    color: #333c4e;
    padding-bottom: 100px;
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
        color: #333c4e;
    }
} 

.decoration{
    padding:40px 0 ;
    div{
        height: 2px;
        width: 230px;
        background-color: lightgray;
    }
}

.cards{
    width: 100%;
    flex-wrap: wrap;

    .card{
        width: calc(100% / 3);
        margin-bottom: 110px;
        h4{
            font-size: 15px;
            font-weight: 200;
            color: #333c4e;
            padding-bottom: 35px;
            padding-top: 25px;
        }

        p{
            font-size: 13px;
            font-weight: 100;
            color: #838383;
            padding-bottom:25px ;
        }
        
    }
}



</style>