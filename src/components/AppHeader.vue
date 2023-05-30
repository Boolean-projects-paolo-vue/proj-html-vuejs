<script>
import AppNavbar from './Header/AppNavbar.vue';

export default {
components:{
    AppNavbar,
},
data() {
        return {
            ArrayHarder: [
                {
                    title: 'Home',
                },
                {
                    title: 'Service',
                },
                {
                    title: 'Courses',
                },
                {
                    title: 'About',
                },
                {
                    title: 'FAQ',
                },
                {
                    title: 'Blog',
                },
                {
                    title: 'Contact Us',
                },
            ],
        };
    },
}
</script>

<template>

    <div class="container_header">
        <section class="section_nav d-flex align-item-between pt-2">
            <div class="navbar d-flex flex-column align-items-center" style="color:white; font-weight: 400;">
                <div class="sub_navbar_info d-flex justify-content-between align-items-center">
                    <div class="d-flex justify-content-between" style="width:75%; font-size: 13px;">
                        <span>
                            <i class="fa-solid fa-location-dot p-1"
                            style="font-size: 11px;">
                            </i>
                            6767 Santa Monica Blvd, Los Angeles; CA 90038
                        </span>
                        <div>
                            <i class="fa-solid fa-phone p-1" 
                            style="font-size: 10px; ">
                        </i>
                            Call Now 123-456-7890
                        </div>
                    </div>

                    
                    <div class="d-flex justify-content-end" style="width: 30%; font-size: 15px;">
                        <button class="px-5 py-2 rounded-3 " style="font-weight: 700; background-color: white; border:0;">Donate</button>
                    </div> 
                </div>

                <div class="sub_navbar d-flex flex-row justify-content-between pb-2">
                    <img src="./../assets/chess/images/mt-2236-home-logo.png" alt="" class="logo" style="height: 100%;">
                    <div class=" list d-flex flex-row justify-content-center align-items-center">
                       <AppNavbar 
                            v-for="index in ArrayHarder" 
                            :key="index.title"
                            :title="index.title"
                            style="font-size: 14px;"
                       /> 
                    </div>
                </div>
            </div>
        </section>
        
        <section class="section_title">
            <button class="button_telephone py-3 text-center" style="background-color: white; width: 4%; border:0">
                    <i class="fa-solid fa-phone p-1" style="font-size: 32px;"></i>
            </button>
            <div class="container_title d-flex flex-column" style="width:60%; color:white;">
                
                <div>
                    <button class="first_button_nav d-flex align-items-center rounded-3" 
                    style="font-size: 9px; background-color: #FFCD18; font-weight: 700; border:0;">
                        WELCOME
                    </button>
                </div>
                <h1 
                class="mb-3"
                style="font-size: 60px; font-weight: 700;">
                    ACADEMIC CHESS FOR 
                    <span 
                    style="color:#FFCD18; font-style: oblique;">
                        EVERYONE
                    </span> 
                </h1>

                <p class="" style=" width:70%; font-size: 16px; font-weight: 500;">We are dedicated to broadening and developing chess as art, recreation, and as a significat element of culture in Northern California.</p>
                
                <div class="mt-2">
                    <button 
                    class=" button_nav py-2 rounded-1 me-3 border-0" 
                    style="color:black; font-weight: 600; background-color: #FFCD18 ">
                        Enroll Now
                    </button>

                    <button 
                    class=" button_nav py-2 rounded-1" 
                    style="border: 1px solid white; background-color: transparent; color:white; font-weight: 600;">
                        Learn More
                    </button>
                </div>
                
            </div>
            
        </section>
        
        
        
    </div>

</template>


<style lang="scss">
    
    i{ 
    color:#FFCD18;
    };

    .container_header{
        background-image: url(./../assets/chess/images/mt-2236-home-bg1.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 45rem;
    }
    
    .section_nav{
        background-color: rgba(4, 7, 55, 0.338);
        height: 16%;
    }

    .navbar{
        width: 60%;
        height: 100%;
        margin: auto;   
    }

    .sub_navbar_info{
        width: 100%;
        
    }

    .sub_navbar{
        width: 100%;
    }


    .list{
        height: 100%;
    }



    .section_title{
        height: 84%;
        width: 60%;
        margin: auto;
        padding-top: 5.5rem;
    }

    .button_telephone{
        border-radius: 100%;
        position:absolute;
        left: 0.5rem;
        top: 23.5rem;
    }

    .container_title{
        position: relative;
    }

    

    .first_button_nav{
        padding-inline: 0.7rem;
    }

    .button_nav{
        padding-inline: 2.4rem;
    }


    .button_telephone:hover{
        scale: 0.9;
    }

</style>