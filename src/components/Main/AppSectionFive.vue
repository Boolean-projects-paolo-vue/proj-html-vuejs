<script>
export default {

}
</script>

<template>
    <section class="section_five">
        <div class="text-center" style="width: 100%;">
            <h2 style="font-weight: 700;">Our Events</h2>
            <h5 style="color: grey; font-size: 23px ;">Chess is fun and we are happy prove it at our events!</h5>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-3 offset-1">
                    <div class="sub_col">
                        <img src="./../../assets/chess/images/mt-2236-home-img4.jpg" alt="" class="img-fluid ms-2"
                        style="width: 300px;">
                    </div>
                </div>
                <div class="col-4">
                    <div class="sub_col pt-4">
                        <h5 style="font-weight: 700;">Grand Summer Tournament of 2021</h5>
                        <p class="pe-4"
                        style="font-size: 13.5px;">
                        Join us for the Grand Summer Tournament 2021, Held every year on the first Sunday of summer, our Grand Summer Tournament chess masters and beginners from North California.
                        <br>
                        We have competitions for different levels of chess mastery with amazing prizes awarded at each level. 
                        </p>
                    </div>
                    
                </div>
                <div class="col-3">
                    <div class="sub_col pb-3" style="width: 68%;">
                        <button 
                        class=" button_nav py-2 rounded-1 border-0 mt-2 ms-5" 
                        style="color:black; font-weight: 600; background-color: #FFCD18;">
                            Register
                        </button>
                    </div> 
                </div>
            </div>
            <div class="container">
                <div class="row">
                    <div class="col-3 offset-1">
                        <div class="sub_col">
                            <img src="./../../assets/chess/images/mt-2236-home-img5.jpg" alt="" class="img-fluid"
                            style="width: 300px;">
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="sub_col pt-4">
                            <h5 style="font-weight: 700;">Wolrd Chess Day</h5>
                            <p class="pe-2"
                            style="font-size: 13.5px;">
                            Celebrated on July 20 every year, World Chess Day is one of the biggest events at our school. Be ready for fun tournaments and big prizer. Registration is obligatory!
                            </p>
                        </div>
                        
                    </div>
                    <div class="col-3">
                        <div class="sub_col pb-2" style="width: 68%;">
                            <button 
                            class=" button_nav py-2 rounded-1 border-0 mt-2 ms-5" 
                            style="color:black; font-weight: 600; background-color: #FFCD18;">
                                Register
                            </button>
                        </div> 
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    .button_nav{
        padding-inline: 3rem;
    }

    .container{
        padding-top: 3rem;
        padding-bottom: 3rem; 
    }

    .section_five{
        margin-top: 4rem;
    }

    
    .sub_col{
        width: 100%;
        height: 100%;
        margin-left: 3.5rem;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
</style>