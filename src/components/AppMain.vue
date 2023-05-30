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
                <div class="col-3 offset-1">
                    <div class="d-flex flex-column align-items-center pt-1 ms-1">
                        <h2 style="font-weight: 700; color: black;">Latest News</h2>
                        <div  class="line my-4" style=" width: 22%; border: 2px solid #FFCD18;"></div>
                        <button 
                            class=" button_nav py-2 ms-4 rounded-1" 
                            style="border: 1px solid black; background-color: transparent; font-weight: 600;">
                                View Other Posts
                        </button>
                    </div>
                </div>
                <div class="col-3">
                    <div class="immagine" style="width: 100%;">
                        <img src="./../assets/chess/images/mt-2236-blog-img1.jpg" alt="" class="img-fluid">
                        <h6 class="mt-3">The most common mistakes when managing personal finaces</h6>
                    </div>
                </div>
                <div class="col-3">
                    <div class="immagine" style="width:100%">
                        <img src="./../assets/chess/images/mt-2236-blog-img2.jpg" alt="" class="img-fluid">
                        <h6 class="mt-3">Methods of the recruitment</h6>
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
        width: 90%;
        margin: auto;
        padding-top: 5rem;
        padding-bottom: 6rem;  
    }
    
    .immagine{
        margin-left: 3.5rem;
    }

    .line{
        margin-right: 8rem ;
    }
    </style>