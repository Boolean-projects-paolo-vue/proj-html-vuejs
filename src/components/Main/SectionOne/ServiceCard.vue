<script>
export default {
    props: {
        image: String,
        title: String,
        description: String,
    } 
}
</script>


<template>
    <div class="sub_col">
        <div class="item_service">
            <div style="width: 20%;"><img :src="image" alt="" class="pb-3 img-fluid"></div>
            <h6 style="font-weight: 600;">{{ title }}</h6>
            <p class="p_main">{{ description }}</p> 
        </div>
        
    </div>
</template>



<style>
    .sub_col{
        width: 49%;
        padding-top: 0.7rem;
        padding-left: 1.2rem;
        padding-right: 4.5rem; 
    }

    .p_main{
        font-size: 15px;
        color: grey;
    }

    .span_main{
        font-size: 15px;
        color: grey;
    }
</style>