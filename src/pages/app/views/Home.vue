<template>
  <div class="home">
    <img src="@/common/assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App!"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/pages/app/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
