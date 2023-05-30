<script>
export default {

}
</script>


<template>
    <section class="section_four d-flex align-items-center justify-content-between">
        <div class="d-flex align-items-center justify-content-between" style="width: 61%; margin: auto; ">
            <div>
                <h1 style="font-weight: 600; color: white;">TAKE THE <span style="color:#FFCD18">FIRST STEP</span></h1>
                <h6 style="color:white">The fascinating world of chess has its doors open anyone</h6>
            </div>
            <div class="mb-4 me-1">
                <button 
                class=" button_nav chess py-2 rounded-1 border-0 mt-2" 
                style="color:black; font-weight: 600; background-color: #FFCD18;">
                    View More
                </button>
            </div>
        </div>
    </section>
</template>


<style lang="scss" scoped>

    .button_nav{
        padding-inline: 2rem;
    }

    .section_four{
    margin-top: 3rem;
    height: 17rem;
    background-image: url(./../../assets/chess/images/mt-2236-home-bg2.jpg);
    background-repeat:no-repeat;
    background-size: cover;
    display: flex;
    align-items: center;
    }

    .chess{
        margin-right: 6.2rem;
    }
</style>