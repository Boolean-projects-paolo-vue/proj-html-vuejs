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
    .list_component{
        padding-inline: 0.6rem;
    }
</style>