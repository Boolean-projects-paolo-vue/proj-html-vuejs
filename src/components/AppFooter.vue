<script>
export default {

}
</script>

<template>
<section class="section_footer">
    <div class="container d-flex justify-content-between" style="color: white">
        <div class="footer left d-flex flex-column justify-content-between">
            <div style="width: 80%">
                <img src="./../assets/chess/images/mt-2236-home-logo.png" alt="" class="img-fluid">
            </div>
            <div>
                <p style="font-size: 13px;">Copyright 2021, All right Riserved.</p> 
            </div>
        </div>
        
        <div class="footer central">
            <p>Follow Us</p>
            <div class="d-flex pt-2">
                <div class="icon py-1 rounded-2 mx-1" style="border: 1px solid white">
                    <i class="fa-brands fa-facebook-f" style="color: white; font-size: 12px;"></i>
                </div>
                <div class="icon_2 py-1 rounded-2 mx-1" style="border: 1px solid white">
                    <i class="fa-brands fa-telegram" style="color: white; font-size: 14px;"></i>
                </div>
                <div class="icon_3 py-1 rounded-2 mx-1" style="border: 1px solid white">
                    <i class="fa-brands fa-instagram" style="color: white; font-size: 12px;"></i>
                </div> 
            </div> 
        </div>
        <div class="footer">
            <div style="width: 95%; font-size: 14px;">
                <p>Subscribe to get the lastest news, course updates, discouts, events</p>
            </div>
            
            <input type="text" placeholder="enter your e-mail here *" class=" px-3" style="width: 100%; font-size:12px; padding: 0.8rem 0 0.8rem 0;">
            <br>
            <button 
                class=" button_nav py-2 rounded-1 border-0 mt-3" 
                style="color:black; font-weight: 600; background-color: #FFCD18;">
                Subscribe
            </button>
        </div>
    </div>
</section>
   
  
</template>


<style lang="scss" scoped>

    .button_nav{
        padding-inline: 1.5rem;
    } 

    .section_footer{
        background-color: rgb(28, 28, 28);
    }
    .container{
        width: 58.5%;
        height: 18rem;
        margin-left: 23rem ;
        
    }

    .footer{
        height: 100%;
        padding-top: 3.5rem ;
    }
    
    .icon{
        padding-inline: 0.8rem;
    }

    .icon_2{
        padding-inline: 0.6rem;
    }
    .icon_3{
        padding-inline: 0.6rem;
    }
</style>