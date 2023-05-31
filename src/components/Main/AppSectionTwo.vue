<script>
export default {

}
</script>



<template>
    <section class="second_section" style="background-color: #FFCD18;">
        <div class="d-flex" >
            <div><img src="./../../assets/chess/images/mt-2236-home-gallery1.jpg" alt="" class="img-fluid"></div>
            <div><img src="./../../assets/chess/images/mt-2236-home-gallery2.jpg" alt="" class="img-fluid"></div>
            <div><img src="./../../assets/chess/images/mt-2236-home-gallery3.jpg" alt="" class="img-fluid"></div>
            <div><img src="./../../assets/chess/images/mt-2236-home-gallery4.jpg" alt="" class="img-fluid"></div>
        </div>
        <div class="sub_section d-flex flex-row align-items-center justify-content-between">
            <div class="logo_horse"><img src="./../../assets/chess/images/mt-2236-home-icon5.png" alt="" class="img-fluid"></div>
            <div class="play_learn">
                <h2 style="font-weight: 700;">PLAY & LEARN</h2>
                <h5>Take a look into our day to day life here at Chess School</h5>
            </div>
            <div class="d-flex flex">
                <button 
                    class=" button_nav py-2 rounded-1" 
                    style="border: 2px solid black; background-color: transparent; font-weight: 600;">
                        Learn More
                </button>
            </div>
        </div>
        
    </section>
</template>



<style lang="scss" scoped>

    .button_nav{
        padding-inline: 2rem;
        margin-right: 2.5rem;
    }

    .second_section{
        margin-top: 6rem;
    }

    .sub_section{
        width: 63%;
        padding-right: 4rem;
        padding-left: 0.5rem;
        margin: auto;
        height: 11rem;
    }

    .logo_horse{
        margin-left: 3rem;
    }
    .play_learn{
        margin-right: 3.5rem ;
    }

</style>