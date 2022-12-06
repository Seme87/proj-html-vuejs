<script>
    export default {
        name:"SectionAppointment"
    }
</script>


<template>
    <section class="appointment">

        <div class="s-meet-top container-xs text-center">

            <h2>Make An Appointment</h2>
            <div class="decoration d-flex justify-content-center">
                <div></div>
            </div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit corporis</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Impedit</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing.</p>

            <form action="" class="d-flex container-xs ">
                <input class="col" type="text" nome="nome" placeholder="Name" required>
                <input class="col" type="email" nome="nome" placeholder="Email" required>
                <input class="col" type="number" placeholder="Phone Number" required>
                <input class="col" type="date" placeholder="Appointment Date" required>
                <textarea style="height:100px ;" placeholder="How we can we Help" ></textarea>
                <button class="btn" type="submit">MAKE AN APPOINTMENT</button>
            </form>
            
        </div>

        
    </section>
</template>



<style lang="scss" scoped>

.appointment{
    background-image: url(../assets/make-an-appointment.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 150px 0;
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

form{
    margin-top: 50px;
    padding: 0 30px;
    flex-wrap: wrap;
    
}
.col{
    padding: 10px 20px;
    color: #ffff;
    margin: 10px;
    width:calc(100% / 2 - 20px);
    background-color: inherit;
    border: 1px solid #ffff;
}
textarea{
    margin: 0 10px;
    padding: 10px 20px;
    width: 100%;
    background-color: inherit;
    border: 1px solid #ffff;

}

.btn{
    margin: 0 10px;
    margin-top: 10px;
    width: 100%;
    background-color:#3aafbf ;
    border: none;
}
</style>