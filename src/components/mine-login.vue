<template>
  <div >
      
      <topLogin></topLogin>
      <div>
        <img src="@/assets/122.jpg" alt="">
        <span>我的订单</span>
      </div>
      
  </div>
</template>

<script>
import topLogin from "../components/mine/top-login"

export default {
  components:{
    topLogin
    
  }
}
</script>



<style src="C:\Users\Administrator\Desktop\电影项目.app\filmapp\font_2564752_qwr96ej34tn\iconfont.css">

</style>
<style scoped>

div{overflow: hidden;padding-bottom: 10px; }
  img{display: block;float: left;border-radius: 50%;}
  span{display: block;margin-top: 30px;padding-left: 50px;color: gray;}
</style>