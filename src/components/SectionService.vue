<script>
    export default {
        name:"SectionService"
        
    }
</script>


<template>
    <Section class="service">
        <!-- CARDS -->
        <div class="cards d-flex">
            
            <div class="card first text-center">
                <h5>Emergency Care</h5>
                <img src="../assets/wave-divider.png" alt="LOGO-WAVE">
                <p>Lorem, ipsum dolor sit amet consectetur ipsum dolor sit amet</p>
                <p>Lorem, ipsum dolor sit amet</p>
                <button class="btn">LEARN MORE</button>
            </div>

             <div class="card second text-center">
                <h5>Expert Diagnostic</h5>
                <img src="../assets/wave-divider.png" alt="LOGO-WAVE">
                <p>Lorem, ipsum dolor sit amet consectetur ipsum dolor sit amet</p>
                <p>Lorem, ipsum dolor sit amet</p>
                <button class="btn">LEARN MORE</button>
            </div>

            <div class="card third text-center">
                <h5>Super Reahblitation</h5>
                <img src="../assets/wave-divider.png" alt="LOGO-WAVE">
                <p>Lorem, ipsum dolor sit amet consectetur ipsum dolor sit amet</p>
                <p>Lorem, ipsum dolor sit amet</p>
                <button class="btn">LEARN MORE</button>
            </div>

        </div>
        <!-- CARDS -->

    </Section>
</template>



<style lang="scss" scoped>
.card{
    color: #ffff;
    width: calc(100% / 3);
    padding:70px 40px;
    .btn{
        background-color: inherit;
        border: 1px solid #ffff;
        color: #ffff;
    }
    img{
        padding-bottom: 15px;
    }

    h5{
        padding-bottom: 20px;
        font-size: 20px;
        font-weight: 400;
    }

    p{
        font-size: 20px;
        font-weight: 100;
        padding-bottom: 20px;
    }
}

.first{
    background-color:#3aafbf ;
}

.second{
    background-color:#3597c3 ;
}

.third{
    background-color: #327ec7;
}
</style>