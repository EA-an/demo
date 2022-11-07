<template>
    <div class="top-last-warpper">
            <img src="" alt="">
            <span  v-show="!islogin">登录</span>
            <span  v-show="islogin">个人中心</span>
        </div>
</template>
<script>
export default{
    data(){
        return{
            islogin:false
        }
    },
    methods:{
        login(){

            

        }
    }

}
</script>
<style scoped>


</style>