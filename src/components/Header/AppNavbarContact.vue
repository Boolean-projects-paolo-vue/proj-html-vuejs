<script>
export default {
    props:{
        write: String
    }
    
}
</script>

<template>
    <div class="d-flex">
            <span class="write">{{ write }}</span>
    </div>
</template>

<style>
    .write{ 
        font-size: 14px;
    }

    @media screen and (min-width: 1200px){
        .write{ 
        font-size: 12px;
    }
    }
</style>