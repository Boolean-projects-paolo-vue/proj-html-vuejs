<script>
export default {

}
</script>

<template>
    <section class="section_third">
        <div class="text-center">
            <h2 style="font-weight: 700;">Courses</h2>
            <h5 style="color: grey; font-size: 22px ;">To keep up with the constantly rising standards of play</h5>
        </div>
        <div class="d-flex flex-row pt-4" style="width: 63%; margin: auto;">
            <div class="col-4">
                
                <div class=" card text-center mx-3 border-0">
                    <div><img src="./../../assets/chess/images/mt-2236-home-img1.jpg" alt="" class="img-fluid"></div>
                    <h4 class="px-3 mt-4" style="font-weight: 700;">Garry Kasparov's Masterclass</h4>
                    <p  style="font-size: 14px; padding-inline: 2.5rem; color: grey;">Learn the tips, tricks, and strategies from one of the best masters</p>
                    <h5 class="mt-1" style="font-weight: 800;">$456</h5>
                    <div class="mb-4">
                        <button 
                        class=" button_nav py-2 rounded-1 border-0 mt-2" 
                        style="color:black; font-weight: 600; background-color: #FFCD18;">
                            View More
                        </button>
                    </div>
                </div>
                        
            </div>
            <div class="col-4">
                
                <div class=" card text-center mx-3 rounded-0 border-0">
                    <div><img src="./../../assets/chess/images/mt-2236-home-img2.jpg" alt="" class="img-fluid"></div>
                    <h4 class="px-3 mt-4" style="font-weight: 700;">Online Chess Lessons for Beginners</h4>
                    <p  style="font-size: 14px; padding-inline: 2.5rem; color: grey;">Catered to adults beginners who have a few hours a week to practise</p>
                    <h5  class="mt-1" style="font-weight: 800;">$205</h5>
                    <div class="mb-4">
                        <button 
                        class=" button_nav py-2 rounded-1 border-0 mt-2" 
                        style="color:black; font-weight: 600; background-color: #FFCD18;">
                            View More
                        </button>
                    </div>  
                </div>
                
            </div >
            <div class="col-4 pb-3">
                
                <div class="card text-center mx-3 rounded-0 border-0">
                    <div><img src="./../../assets/chess/images/mt-2236-home-img3.jpg" alt="" class="img-fluid"></div>
                    <h4 class="px-3 mt-4" style="font-weight: 700;">International Chess School Online</h4>
                    <p style="font-size: 14px; padding-inline: 3rem; color: grey;">Chess lessons for children and adults held completely online</p>
                    <h5 class="mt-1" style="font-weight: 800;">$356</h5>
                    <div class="mb-4">
                        <button 
                        class=" button_nav py-2 rounded-1 border-0 mt-2" 
                        style="color:black; font-weight: 600; background-color: #FFCD18;">
                            View More
                        </button>
                    </div>
                </div>
                
            </div>
        </div>
        <div class="d-flex justify-content-center pt-4" style="width: 100%;">
            <button
            class="button_nav py-2 rounded-1"
            style="font-weight: 600; background-color: transparent;"
            >
                View Other Courses
            </button>
        </div>
    </section>
</template>

<style lang="scss" scoped>

    .button_nav{
        padding-inline: 2rem;
    }

    .section_third{
        margin-top: 5rem;
    }

    .card{
        -webkit-box-shadow: 1px 1px 20px 0px rgba(0,0,0,0.75);
        -moz-box-shadow: 1px 1px 20px 0px rgba(0,0,0,0.75);
        box-shadow: 1px 1px 20px 0px rgba(0,0,0,0.75);
    }
    .card:hover{
        scale: 1.1;
    }
</style>