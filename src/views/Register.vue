<template>
  <div class="register">
    <h2 class="title">手机号注册</h2>
    <div class="registerform">
        <van-field v-model="phone" placeholder="请输入手机号" />

        <van-field v-model="password" placeholder="请输入密码" />
        
        <van-button type="primary" size="large">注册</van-button>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import { Cell, Field,Icon,Button  } from 'vant';


export default {
  name: 'login',
  components:{
      [Cell.name]:Cell,
      [Field.name]:Field,
      [Icon.name]:Icon,
      [Button .name]:Button 
  },
  data(){
      return{
          phone:"",
          password:""
      }
  }
  
}

</script>
<style scoped>
.title{
    height: 4rem;
    line-height: 4rem;
    font-size: 1.8rem;
}
.registerform .van-cell{
    padding: 1.5rem;
}
.van-button{
    width: 80%;
    height: 3rem;
    line-height: 3rem;
    border-radius: 2rem;
    background: #33c7b4;
    margin-top: 2rem;
}

</style>



