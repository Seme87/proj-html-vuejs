<script>
    export default {
     name: "SectionSlider"   
    }
</script>


<template>
    <Section class="slider ">
        <div class="d-flex container-small">
            <div class="col">
                <img src="../assets/client-logos-2.png" alt="Client logo">
            </div>
            <div class="col">
                <img src="../assets/client-logos-1.png" alt="client logo 2">
            </div>
            <div class="col">
                <img src="../assets/client-logos-4.png" alt="cliet logo 3">
            </div>
            <div class="col">
                <img src="../assets/client-logos-3.png" alt="">
            </div>
        </div>
    </Section>
</template>



<style lang="scss" scoped>

.slider{
    background-image: url(../assets/rgb-gradient-bar-for-logo-carrasel.jpg);
    background-size: cover;
}
.col{
    width: 25%;
    img{
        max-width: 100%;
    }
    
}
</style>