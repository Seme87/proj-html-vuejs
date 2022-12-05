
<script>

    export default {
        name:"SectionMeet"
        
    }
</script>


<template>
    <section class="meet-section">
        <!-- SEZIONE SUPERIORE MEET -->
        <div class="s-meet-top container-xs text-center">
            <div class="logo">
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

        <!-- SEZIONE INFERIORE MEET -->
        div

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
</style>