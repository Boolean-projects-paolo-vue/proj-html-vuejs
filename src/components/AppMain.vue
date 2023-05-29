<script>
import AppSection from './Main/AppSection.vue';

export default {
    AppSection,

}
</script>

<template>
    <div>
        <AppSection />
    </div>
<section class="first_section">
    <div
    class="first_title_main"
    style="text-align: center;">
        <h1  style="font-weight:700; font-size:35px ;">OUR SERVICES</h1>
        <h5 style="color:grey">We make your child happy day after day</h5>
    </div>
    <div class=" container_col d-flex flex-row justify-content-center">
        <div class="col-4 mx-3">
            <h3>Chess Education</h3>
            <h5>Popular education for your child and you</h5>
            <p class="p_main">Teachers and parents around the world know that chess is not a simple game, It is a great learning tool that will help build your child's executive function skills.</p>
            <div class="p-2">
                <li><img src="./../assets/chess/images/mt-2236-home-icon-bullet.png" alt=""><span class="span_main p-2">Build self-regulation and motivation</span></li>
                <li><img src="./../assets/chess/images/mt-2236-home-icon-bullet.png" alt=""><span class=" span_main p-2">Help with concentration issues</span></li>
                <li><img src="./../assets/chess/images/mt-2236-home-icon-bullet.png" alt=""><span class=" span_main p-2">Learn to plan, organize, and prioritize</span></li>
                <li><img src="./../assets/chess/images/mt-2236-home-icon-bullet.png" alt=""><span class=" span_main p-2">Regulate emotions</span></li>
                <li><img src="./../assets/chess/images/mt-2236-home-icon-bullet.png" alt=""><span class=" span_main p-2">Learn to pay attetion to detail</span></li>
            </div>
        </div>
        <div class="col-4 mx-4">
           <div>
               <div style="width: 10%;"><img src="./../assets/chess/images/mt-2236-home-icon1.png" alt="" class="pb-3 img-fluid"></div>
               <h6 style="font-weight: 600;">Various Age Groups</h6>
               <p class="p_main">We provider chess classes to both children from 5 years old and adults.</p> 
           </div> 
           <div>
               <img src="./../assets/chess/images/mt-2236-home-icon3.png" alt="" class="pb-3">
               <h6 style="font-weight: 600;">Best Chess Players</h6>
               <p class="p_main">Our alumni have won many prestigious chess tournaments in the country.</p> 
           </div>
        </div>
        <div class="col-4 mx-3">
            <div>
               <img src="./../assets/chess/images/mt-2236-home-icon1.png" alt="" class="pb-3">
               <h6 style="font-weight: 600;">Various Age Groups</h6>
               <p class="p_main">We provider chess classes to both children from 5 years old and adults.</p> 
           </div> 
           <div>
               <img src="./../assets/chess/images/mt-2236-home-icon3.png" alt="" class="pb-3">
               <h6 style="font-weight: 600;">Best Chess Players</h6>
               <p class="p_main">Our alumni have won many prestigious chess tournaments in the country.</p> 
           </div>
        </div>
    </div>
</section>
   
  
</template>


<style lang="scss">
    .first_section{
        width: 50%;
        margin: auto;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .first_title_main{
        padding-top: 5rem;
    }

    .col-4{
        background-color: aqua;
    }

    .p_main{
        font-size: 14.5px;
    }
    .span_main{
        font-size: 14px;
    }
</style>