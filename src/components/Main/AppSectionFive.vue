<script>
export default {

}
</script>

<template>
    <section class="section_five">
        <div class="text-center" style="width: 100%;">
            <h2 style="font-weight: 700;">Our Events</h2>
            <h5 style="color: grey; font-size: 20px ;">Chess is fun and we are happy prove it at our events!</h5>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-4" style="width: 350px;">
                    <div class="p-0">
                        <img src="./../../assets/chess/images/mt-2236-home-img4.jpg" alt="" class="img-fluid">
                    </div>
                </div>
                <div class="col-5">
                    <div class="sub_col p-0">
                        <h5 style="font-weight: 700;">Grand Summer Tournament of 2021</h5>
                        <p class="text"
                        style="font-size: 15px;">
                        Join us for the Grand Summer Tournament 2021, Held every year on the first Sunday of summer, our Grand Summar Tournament chess masters and beginners from North California.
                        <br>
                        We have competitions for different levels of chess mastery with amazing prizes awarded at each level.
                        </p>
                    </div>
                    
                </div>
                <div class="col-3">
                    <div class="sub_col p-0 ms-5" style="width: 70%;">
                        <button 
                        class=" button_nav py-2 rounded-1 border-0" 
                        style="color:black; font-weight: 600; background-color: #FFCD18;">
                            Register
                        </button>
                    </div> 
                </div>
            </div>
        </div>

            
        <div class="container">
            <div class="row">
                <div class="col-4" style="width: 350px;">
                    <div class="p-0">
                        <img src="./../../assets/chess/images/mt-2236-home-img5.jpg" alt="" class="img-fluid">
                    </div>
                </div>
                <div class="col-5">
                    <div class="sub_col p-0">
                        <h5 style="font-weight: 700;">World Chess Day</h5>
                        <p class="text"
                        style="font-size: 15px;">
                        Celebrated on July 20 every year, World Chess Day is one of the biggest events at our school. Be ready for fun tournaments and big prizer. Registration is obligatory!
                        </p>
                    </div>
                    
                </div>
                <div class="col-3">
                    <div class="sub_col p-0 ms-5" style="width: 70%;">
                        <button 
                        class=" button_nav py-2 rounded-1 border-0" 
                        style="color:black; font-weight: 600; background-color: #FFCD18;">
                            Register
                        </button>
                    </div> 
                </div>
            </div>
        </div>
    
    </section>
</template>

<style lang="scss" scoped>
    .button_nav{
        width: 85%;
    }

    .section_five{
        margin-top: 4rem;
        padding-bottom: 7rem;
    }

    .container{
        margin: auto;
        padding-left:6rem;
        padding-top: 3rem;       
        transition: transform 0.2s;
        &:hover{
            transform: scale(1.1);
        } 
    }

    

    
    .sub_col{
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    .text{
      padding-right: 3rem;  
    }
</style>