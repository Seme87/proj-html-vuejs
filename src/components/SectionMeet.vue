
<script>

    export default {
        name:"SectionMeet"
        
    }
</script>


<template>

    <section class="meet-section ">

        <!-- SEZIONE SUPERIORE MEET -->
        <div class="s-meet-top container-xs text-center">
            <div class="logo d-flex justify-content-center">
                <img src="../assets/icon-5.png" alt="Logo Meet-doctor">
            </div>
            <h2>MEET OUR DOCTORS</h2>
            <div class="decoration d-flex justify-content-center">
                <div></div>
            </div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit corporis</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing.</p>
            
        </div>
        <!-- SEZIONE SUPERIORE MEET -->

        <!-- SEZIONE INFERIORE MEET  CARDS-->
        <div class="cards d-flex container-small">

            <!-- PRIMA CARD -->
            <div class="card">
                <div class="img-doc">
                    <img src="../assets/doctor-1.jpg" alt="Doctor 1">
                </div>
                
                <div class="name-pro">
                    <h4>JHON SNOW</h4>
                    <H5>Anesthesiologist</H5>
                    <p>Lorem ipsum dolor sit amet consectetur</p>
                    <p>Lorem ipsum dolor sit amet consectetur</p>
                    <p>Lorem ipsum dolor sit amet consectetur</p>

                    <div class="icon">
                        <i class="facebook fa-brands fa-square-facebook"></i>
                        <i class="twitter fa-brands fa-square-twitter"></i>
                        <i class="instagram fa-brands fa-square-instagram"></i>
                    </div>
                </div>
                
            </div>
            <!-- PRIMA CARD -->

            <!-- SECONDA CARD -->
             <div class="card">

                <div class="img-doc">
                    <img src="../assets/doctor-2.jpg" alt="Doctor 1">
                </div>
                
                <div class="name-pro">
                    <h4>TONY STARK</h4>
                    <H5>Cardiologist</H5>
                    <p>Lorem ipsum dolor sit amet consectetur</p>
                    <p>Lorem ipsum dolor sit amet consectetur</p>
                    <p>Lorem ipsum dolor sit amet consectetur</p>

                    <div class="icon">
                        <i class="facebook fa-brands fa-square-facebook"></i>
                        <i class="twitter fa-brands fa-square-twitter"></i>
                        <i class="instagram fa-brands fa-square-instagram"></i>
                    </div>
                </div>
                
            </div>
            <!-- SECONDA CARD -->

            <!-- TERZA CARD -->
             <div class="card">
                <div class="img-doc">
                    <img src="../assets/doctor-3.jpg" alt="Doctor 1">
                </div>
                
                <div class="name-pro">
                    <h4>ANNA SMITH</h4>
                    <H5>Nurse Pratictioner</H5>
                    <p>Lorem ipsum dolor sit amet consectetur </p>
                    <p>Lorem ipsum dolor sit amet consectetur </p>
                    <p>Lorem ipsum dolor sit amet consectetur </p>

                    <div class="icon">
                        <i class="facebook fa-brands fa-square-facebook"></i>
                        <i class="twitter fa-brands fa-square-twitter"></i>
                        <i class="instagram fa-brands fa-square-instagram"></i>
                    </div>
                </div>
                
            </div>
            <!-- TERZA CARD -->

        </div>
        <!-- SEZIONE INFERIORE MEET  CARDS-->
        


    </section>
</template>

<style lang="scss" scoped>
.meet-section{
    padding-bottom: 150px;
    padding-top: 100px;
    background-color:#f7f7f7 ;
}

.s-meet-top{
    color: #333c4e;
    padding-bottom: 65px;
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
    .card{
        width: calc(100% / 3 - 10px);
        margin: 0 10px;

        .img-doc{
            width: 100%;
            img{
                min-width: 100%;
            }
        }
        
        .name-pro{
            padding: 50px 40px;
            background-color:#ffffff;
            h4{
                font-size: 20px;
                font-weight: 300;
                padding-bottom: 20px;
                color: #333c4e;
            }

            h5{
              font-size: 20px;
              font-weight: 100;
              padding-bottom: 40px;
                color: #333c4e;

            }

            p{
                padding-bottom: 20px;
                color: #858f97;
            }

            .icon{
                padding-top: 40px;
            }
        }
    }
}
</style>