<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Wrapper msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Wrapper from '@/components/Wrapper.vue'

export default {
  name: 'Home',
  components: {
    Wrapper
  }
}
</script>
