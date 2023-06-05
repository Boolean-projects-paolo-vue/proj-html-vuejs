<script>
import AppFooterLeft from './Footer/AppFooterLeft.vue'
import AppFooterCentral from './Footer/AppFooterCentral.vue'
import AppFooterRight from './Footer/AppFooterRight.vue'

export default {
  data() {
    return {
        FirstArr:[
            {
                undertitle: 'Copyright 2021, All right Riserved.',
            },
        ],
        SecondArr:[
            {
                secundertitle: 'Follow Us',
            },
        ],
        ThirdArr:[
            {
                thiundertitle: 'Subscribe to get the lastest news, course updates, discouts, events',
            },
        ]
    }
  },  
  components: { 
    AppFooterLeft, 
    AppFooterCentral,
    AppFooterRight, 
    },
}
</script>

<template>
<section class="section_footer">
    <div class="container d-flex justify-content-between" style="color: white">
       <AppFooterLeft 
        v-for="index in FirstArr" 
        :key="index.undertitle"
        :undertitle="index.undertitle"
       />
        
       <AppFooterCentral
        v-for="index in SecondArr" 
        :key="index.secundertitle"
        :secundertitle="index.secundertitle" 
       />

       <AppFooterRight 
        v-for="index in ThirdArr" 
        :key="index.thiundertitle"
        :thiundertitle="index.thiundertitle" 
       />
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
    
    
</style>