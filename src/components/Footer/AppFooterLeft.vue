<script>
export default {
    props:{
        undertitle: String
    }
}
</script>


<template>
     <div class="footer left d-flex flex-column justify-content-between">
            <div style="width: 80%">
                <img src="./../../assets/chess/images/mt-2236-home-logo.png" alt="" class="img-fluid">
            </div>
            <div>
                <p style="font-size: 13px;">{{ undertitle }}</p> 
            </div>
        </div>
</template>


<style lang="scss" scoped>

</style>