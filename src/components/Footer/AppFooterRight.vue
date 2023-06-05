<script>
export default {
    props:{
        thiundertitle: String
    }
}
</script>


<template>
    <div class="footer">
        <div style="width: 95%; font-size: 14px;">
            <p>{{ thiundertitle }}</p>
        </div>
        
        <input type="text" placeholder="enter your e-mail here *" class=" px-3" style="width: 100%; font-size:12px; padding: 0.8rem 0 0.8rem 0;">
        <br>
        <button 
            class=" button_nav py-2 rounded-1 border-0 mt-3" 
            style="color:black; font-weight: 600; background-color: #FFCD18;">
            Subscribe
        </button>
    </div>
</template>


<style lang="scss" scoped>



</style>