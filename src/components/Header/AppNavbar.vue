<script>
export default {
    props:{
        title: String,
    }   
};
</script>

<template>
    <div class="list_component">{{ title }}</div>
</template>


<style lang="scss">
    .sub_navbar{
        width: 100%;
    }

    .list_component{
        padding-inline: 0.6rem;
    }

    .list_component:hover{
        color: #FFCD18;
        cursor: pointer;
    }

    @media screen and (min-width: 1200px){
    
    }
</style>