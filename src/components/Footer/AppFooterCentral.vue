<script>
export default {
    props:{
        secundertitle: String
    }
}
</script>


<template>
    <div class="footer central">
        <p>{{ secundertitle }}</p>
        <div class="d-flex pt-2">
            <div class="icon py-1 rounded-2 mx-1" style="border: 1px solid white">
                <i class="fa-brands fa-facebook-f" style="color: white; font-size: 12px;"></i>
            </div>
            <div class="icon_2 py-1 rounded-2 mx-1" style="border: 1px solid white">
                <i class="fa-brands fa-telegram" style="color: white; font-size: 14px;"></i>
            </div>
            <div class="icon_3 py-1 rounded-2 mx-1" style="border: 1px solid white">
                <i class="fa-brands fa-instagram" style="color: white; font-size: 12px;"></i>
            </div> 
        </div> 
    </div>
</template>


<style lang="scss" scoped>
    .icon{
        padding-inline: 0.8rem;
        transition: transform 0.2s;
        &:hover{
            transform: scale(1.1);
        }
    }

    .icon_2{
        padding-inline: 0.6rem;
        transition: transform 0.2s;
        &:hover{
            transform: scale(1.1);
        }
    }
    .icon_3{
        padding-inline: 0.6rem;
        transition: transform 0.2s;
        &:hover{
            transform: scale(1.1);
        }
    }
</style>