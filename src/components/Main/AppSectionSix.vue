<script>
export default {

}
</script>

<template>
    <section class="section_six">
        <div class="container">
            <div class="row">
                <div class="col-4">
                    <div class=" News d-flex flex-column align-items-center">
                        <h1 style="font-weight: 700; color: black;">Latest News</h1>
                        <div  class="line my-4" style="width: 22%; border: 2px solid #FFCD18;"></div>
                        <button 
                            class=" button_nav py-2 me-3 rounded-1" 
                            style="border: 1px solid black; background-color: transparent; font-weight: 600;">
                                View Other Posts
                        </button>
                    </div>
                </div>
                <div class="col-4">
                    <div class="immagine" style="width:100%;">
                        <img src="./../../assets/chess/images/mt-2236-blog-img1.jpg" alt="" class="img-fluid">
                        <h6 class="mt-3">The most common mistakes when managing personal finaces</h6>
                    </div>
                </div>
                <div class="col-4">
                    <div class="immagine" style="width:100%">
                        <img src="./../../assets/chess/images/mt-2236-blog-img2.jpg" alt="" class="img-fluid">
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
        width: 62%;
        padding-top: 5rem;
        padding-bottom: 6rem;  
        margin-left: 19rem;
        
    }

    
    .immagine{
        display: flex;
        justify-content: center;
        flex-direction: column;
        
    }

    .line{
        margin-right: 9.2rem ;
    }
</style>