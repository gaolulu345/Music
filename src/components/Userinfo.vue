<template>
  <div class="userinfo">
      <h2>用户信息</h2>
      <div class="avatar"></div>
    
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
}
.avatar{
    width: 3rem;
    height: 3rem;
    border-radius: 50%;
    background: #fff;
    
}

</style>


