<script>
import AppSectionOne from './Main/AppSectionOne.vue';
import AppSectionTwo from './Main/AppSectionTwo.vue';
import AppSectionThird from './Main/AppSectionThird.vue';
import AppSectionFour from './Main/AppSectionFour.vue';
import AppSectionFive from './Main/AppSectionFive.vue';


export default {
    components:{
        AppSectionOne,
        AppSectionTwo,
        AppSectionThird,
        AppSectionFour,
        AppSectionFive,
        
    }
    

}
</script>

<template>
    <AppSectionOne />
    <AppSectionTwo />
    <AppSectionThird />
    <AppSectionFour />
    <AppSectionFive />
    <section class="section_six">
        <div class="container">
            <div class="row">
                <div class="col-4">
                    <div class="d-flex flex-column align-items-center pt-1">
                        <h2 style="font-weight: 700; color: black;">Latest News</h2>
                        <div  class="line my-4" style=" width: 18%; border: 2px solid #FFCD18;"></div>
                        <button 
                            class=" button_nav py-2 ms-4 rounded-1" 
                            style="border: 1px solid black; background-color: transparent; font-weight: 600;">
                                View Other Posts
                        </button>
                    </div>
                </div>
                <div class="col-4">
                    <div class="immagine" style="width: 90%;">
                        <img src="./../assets/chess/images/mt-2236-blog-img1.jpg" alt="" class="img-fluid">
                        <h5 class="mt-3">The most common mistakes when managing personal finaces</h5>
                    </div>
                </div>
                <div class="col-4">
                    <div style="width: 90%">
                        <img src="./../assets/chess/images/mt-2236-blog-img2.jpg" alt="" class="img-fluid">
                        <h5 class="mt-3">Methods of the recruitment</h5>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>


<style lang="scss" scoped>

    
    .section_six{
        background-color: #faf9f9;
    }
    .container{
        margin: auto;
        padding-top: 6rem;
        padding-bottom: 6rem;  
    }
    
    .immagine{
        margin-left: 2rem;
    }

    .line{
        margin-right: 7rem ;
    }
    </style>