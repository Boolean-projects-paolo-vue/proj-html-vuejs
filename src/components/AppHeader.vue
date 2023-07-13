<script>
import AppNavbar from './Header/AppNavbar.vue';
import AppNavbarContact from './Header/AppNavbarContact.vue';

export default {
components:{
    AppNavbar,
    AppNavbarContact,
},
data() {
        return {
            FirstArrayHarder: [
                {
                    write:'6767 Santa Monica Blvd, Los Angeles, CA 90038',
                },
                {
                    write:'Call Now 123-456-7890',
                }
            ],
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
    <section class="section_header">
        <div class="container_header">
            <section class="section_nav">
                <div class="d-flex flex-column" style="height: 100%">
                    <div class="first_navbar d-flex flex-row align-items-center" >
                        <i class="fa-solid fa-location-dot px-1"></i>
                        <i class="fa-solid fa-phone icon_telephone"></i>
                        <div class="d-flex flex-row justify-content-between align-items-center" style="width: 72%;">
                            <AppNavbarContact
                            v-for="element in FirstArrayHarder" 
                            :key="element.write"
                            :write="element.write"
                            />
                        </div>
                        
                        
                        <div class=" div_button d-flex justify-content-end" style="font-size: 15px;">
                            <button class="button_nav px-5 py-2 rounded-3" style="font-weight: 700; background-color: white; border:0;">Donate</button>
                        </div>  
                    </div>
                    
                    <div class="navbar d-flex justify-content-between align-items-center" style="color:white; font-weight: 400;"> 
                        <div style="height: 55%;"><img src="./../assets/chess/images/mt-2236-home-logo.png" alt="" class="logo img-fluid" style="height: 100%;"></div>   
                        
                        <div class="d-flex flex-row">
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
                        <i class=" icon_button_telephone fa-solid fa-phone p-1"></i>
                </button>
                <div class="container_title d-flex flex-column" style="width:60%; color:white;">
                
                    <div>
                        <button class="first_button_nav rounded-3" 
                        style="font-size: 10px; background-color: #FFCD18; font-weight: 700; border:0;">
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
                
                    <div class="mt-4">
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
    </section>    
    <!-- <div class="sub_navbar_info d-flex justify-content-between align-items-center">
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
                            <button class="button_nav px-5 py-2 rounded-3 " style="font-weight: 700; background-color: white; border:0;">Donate</button>
                        </div> 
                    </div> -->
    

</template>


<style lang="scss">
    
    .fa-phone{ 
    color:#FFCD18;
    };

    .fa-location-dot{
      color: #FFCD18;  
    }

    .section_header{
        background-image: url(./../assets/chess/images/mt-2236-home-bg1.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 50rem;
    }

    
    .section_nav{
        background-color: rgba(1, 2, 14, 0.338);
        height: 7rem;
        color: white;
    }



    .first_navbar{
        width: 61%;
        height: 50%;
        margin: auto;
        position: relative;
    }

    .div_button{
        padding-left:9.2rem
    }
    
    .button_nav{
        padding-inline: 2rem;
    }



    .navbar{
        width: 61%;
        height: 50%;
        margin: auto;   
    }



    .section_title{
        height: 84%;
        width: 61%;
        margin: auto;
        padding-top: 7rem;
    }

    .button_telephone{
        border-radius: 100%;
        position:absolute;
        left: 0.5rem;
        top: 26rem;
        transition: transform 0.2s;
        &:hover{
            transform: scale(0.9);
        }
    }

    .icon_button_telephone{
        font-size: 32px;
        @media screen and (max-width: 1200px){
            font-size:15px;
        }
    }

    .container_title{
        position: relative;
        padding-right:2rem;
    }

    
    .icon_telephone{
        position: absolute;
        left: 50rem;
    }

    .first_button_nav{
        padding-inline: 0.7rem;
    }

    .button_nav{
        padding-inline: 2.4rem;
        transition: transform 0.2s;
        &:hover{
            transform: scale(0.95);
        }
    }


   

</style>