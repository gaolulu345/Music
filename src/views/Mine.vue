<template>
  <div class="mine">
    我的
    <Userinfo></Userinfo>
    <Menu></Menu>
  </div>
</template>

<script>
// @ is an alias to /src
import Userinfo from '@/components/Userinfo'
import Menu from '@/components/MineMenu'

export default {
  name: 'mine',
  components: {
    Userinfo,
    Menu
  }
}
</script>


