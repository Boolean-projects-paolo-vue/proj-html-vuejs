<script>
export default{

};
</script>

<template>
    <section class="first_section">
        <div
        class="first_title_main"
        style="text-align: center;">
            <h1  style="font-weight:700; font-size:35px ;">OUR SERVICES</h1>
            <h4  style="color:grey; font-size: 23px;">We make your child happy day after day</h4>
        </div>
        <div class=" container_col d-flex justify-content-center">
            <div class="row">
                <div class="col-4">
                    <div class="sub_col3">
                        <h4 style="font-weight: 700;">Chess Education</h4>
                        <h6>Popular education for your child and you</h6>
                        <p class="p_main">Teachers and parents around the world know that chess is not a simple game, It is a great learning tool that will help build your child's executive function skills.</p>
                        <div class="p-2">
                            <li><img src="./../../assets/chess/images/mt-2236-home-icon-bullet.png" alt=""><span class="span_main p-2">Build self-regulation and motivation</span></li>
                            <li><img src="./../../assets/chess/images/mt-2236-home-icon-bullet.png" alt=""><span class=" span_main p-2">Help with concentration issues</span></li>
                            <li><img src="./../../assets/chess/images/mt-2236-home-icon-bullet.png" alt=""><span class=" span_main p-2">Learn to plan, organize, and prioritize</span></li>
                            <li><img src="./../../assets/chess/images/mt-2236-home-icon-bullet.png" alt=""><span class=" span_main p-2">Regulate emotions</span></li>
                            <li><img src="./../../assets/chess/images/mt-2236-home-icon-bullet.png" alt=""><span class=" span_main p-2">Learn to pay attetion to detail</span></li>
                        </div>
                    </div>  
                </div>

                <div class="col-4">
                    <div class="sub_col">
                        <div style="width: 20%;"><img src="./../../assets/chess/images/mt-2236-home-icon1.png" alt="" class="pb-3 img-fluid"></div>
                        <h6 style="font-weight: 600;">Various Age Groups</h6>
                        <p class="p_main">We provider chess classes to both children from 5 years old and adults.</p> 
                    </div> 
                    <div class="sub_col">
                        <div style="width: 20%;"><img src="./../../assets/chess/images/mt-2236-home-icon3.png" alt="" class="pb-3 img-fluid"></div>
                        <h6 style="font-weight: 600;">Best Chess Players</h6>
                        <p class="p_main">Our alumni have won many prestigious chess tournaments in the country.</p> 
                    </div>
                </div>
                <div class="col-4">
                    <div class="sub_col2">
                        <div style="width: 19%;"><img src="./../../assets/chess/images/mt-2236-home-icon2.png" alt="" class="pb-3 img-fluid"></div>
                        <h6 style="font-weight: 600;">Top Chess Variants</h6>
                        <p class="p_main">We don't only teach classical chess but also other top variants of this game</p> 
                    </div> 
                    <div class="sub_col2">
                        <div style="width: 19%;"><img src="./../../assets/chess/images/mt-2236-home-icon4.png" alt="" class="pb-3 img-fluid"></div>
                        <h6 style="font-weight: 600;">Best Chess Players</h6>
                        <p class="p_main">Our students know all the best chess openings and how to use them.</p> 
                    </div>
                </div>
            </div>
            
            <div class="d-flex justify-content-start pt-3" style="width:100%;">
            <button 
                class=" button_nav py-2 rounded-1 me-3 border-0" 
                style="color:black; font-weight: 600; background-color: #FFCD18;">
                Learn More
            </button>
        </div>
            
        </div>
          
    </section>
</template>

<style lang="scss" scoped>

    .button_nav{
        padding-inline: 2rem;
    }

    .first_title_main{
        padding-top: 6rem;
    }

    .container_col{
        width: 65%;
        margin: auto;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }


    .sub_col{
        padding-top: 0.7rem;
        padding-left: 1.2rem;
        padding-right: 4.5rem;
    }

    .sub_col2{
        padding-top: 0.8rem;
        padding-right: 5.5rem;
    }

    .sub_col3{
        padding-right: 5rem;
    }

    .p_main{
        font-size: 14px;
        color: grey;
    }
    .span_main{
        font-size: 14px;
        color: grey;
    }
</style>