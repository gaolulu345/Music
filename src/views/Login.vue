<template>
  <div class="login">
    <h2>登录</h2>
    <img src="../assets/56f.jpg">
    <div class="loginform">
        <van-field
            v-model="username"
            clearable
            label="用户名"
            left-icon="contact"
            right-icon="question-o"
            placeholder="请输入用户名"
            @click-right-icon="$toast('question')"
        />

        <van-field
            v-model="password"
            type="password"
            label="密码"
            left-icon="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1562908947643&di=37bb180d8092aa8d797fe84f7127a8e2&imgtype=0&src=http%3A%2F%2Fpic.51yuansu.com%2Fpic2%2Fcover%2F00%2F45%2F39%2F5814e2a022cdc_610.jpg"
            right-icon="browsing-history-o"
            placeholder="请输入密码"
        />
        <div class="other">
            <span class="forget">忘记密码?</span><span class="register" @click="register">注册账号</span>
        </div>
        <van-button type="primary" size="large">登录</van-button>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import { Cell, CellGroup,Field,Icon,Button  } from 'vant';


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
          username:"",
          password:""
      }
  },
  methods:{
      register(){
          this.$router.push({path:'/register'})
      }
  }
  
}

</script>
<style scoped>
img{
    width: 100%;
}
.login .loginform{
    width: 84%;
    margin: 0 auto;
    margin-top: 22%;
}
.van-button{
    width: 80%;
    height: 3rem;
    line-height: 3rem;
    border-radius: 2rem;
    background: #33c7b4;
    margin-top: 1rem;
}
.login .other{
    padding: 1.6rem;
    overflow: hidden;
    color: #33c7b4;
}
.login .forget{
    float: left;
}
.login .register{
    float: right;
}
.van-cell{
    padding: 1.5rem;
    line-height: 2.6rem;
}
</style>



