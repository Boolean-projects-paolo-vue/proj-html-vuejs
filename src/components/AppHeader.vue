<script>
export default {

}
</script>

<template>

    <div class="container_header">
        <section class="section_nav">
            <div class="navbar d-flex flex-column align-items-center" style="color:white">
                <div class="sub_navbar_info d-flex justify-content-between">
                    <span>6767 Santa Monica Blvd, Los Angeles; CA 90038</span> 
                    <span>Call Now 123-456-7890</span>
                    <button>Donate</button>
                </div>

                <div class="sub_navbar d-flex flex-row justify-content-between">
                    <img src="./../assets/chess/images/mt-2236-home-logo.png" alt="">
                    <ul class="d-flex flex-row">
                        <li>Home</li>
                        <li>Services</li>
                        <li>Courses</li>
                        <li>About</li>
                        <li>FAQ</li>
                        <li>Blog</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
          
            </div>
        </section>
        
        
        <div>
            
        </div>
        
        
    </div>

</template>


<style lang="scss">
    
    .section_nav{
        background-color: rgba(0, 0, 0, 0.338);
        height: 20%;
    }

    .container_header{
        background-image: url(./../assets/chess/images/mt-2236-home-bg1.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 35rem;
    }
    
    .navbar{
        max-width: 70%;
        background-color: aquamarine;
        margin: auto;
        
    }

    .sub_navbar_info{
        width: 100%;
    }

    .sub_navbar{
        width: 100%;
    }
</style>