<template>
    <div>
     这是商品列表页面
     <span>{{$route.params.goodsId}}</span>
     <br/>
        <span>{{$route.params.name}}</span>
    </div>
</template>
<script>
    export default{
        data(){
            return {
                msg:'hellow vue'
            }
        }
    }
</script>