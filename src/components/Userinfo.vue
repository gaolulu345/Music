<template>
  <div class="userinfo">
      <h2>用户信息</h2>
      <div class="avatar"></div>
      <div class="name">用户名<span>♀</span></div>
    
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'


export default {
  name: 'userinfo',
}
</script>

<style scoped>
.userinfo{
    height:10rem;
    background: #666;
    position: relative;
}
.avatar{
    width: 4.5rem;
    height: 4.5rem;
    border-radius: 50%;
    background: #fff;
    position: absolute;
    top: 3rem;
    left: 3rem;
}
.name{
    position: absolute;
    top: 4rem;
    left: 10rem;
    font-size: 1.6rem;
}
.name span{
    margin-left: 1rem;
}

</style>


