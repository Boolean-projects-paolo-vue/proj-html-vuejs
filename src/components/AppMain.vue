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
        <div class="container" >

        </div>
    </section>

</template>


<style lang="scss" scoped>

    .section_six{
        background-color: #E8E8E8;
    }
    .container{

    }
</style>