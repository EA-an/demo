<template>
    <div class="warpper w">
        <div class="top-left-warpper">
            <span>西瓜</span>
        </div>
        <div class="top-center-warpper">
            <span>首页</span>
        </div>
        <div class="top-center-warpper">
            <span>电影</span>
        </div>
        <div class="top-center-warpper">
            <span>电视剧</span>
        </div>
        <div class="top-search">
            <input type="text"> 
            <button>搜索</button>  
        </div>
        <user/>
    </div>
</template>
<script>
import user from "./user.vue"
export  default{
    components:{user}
}
</script>

<style scoped>
    .warpper{
        display: flex;
        justify-content: space-around;
    }
    .warpper>div{
        margin-top: 20px;
    }
    .warpper>div span{
        font-weight: 900;
    }
    .warpper>div span:hover{
        color: red;
    }
    .top-center-warpper{
        margin-left:-200px;
    }
    .top-search input{
        height:25px;
        width:300px;
        margin-left:-50px;
    }
    .top-search button{
        height: 28.98px;
        
    }
    
</style>
