<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/real-madrid-logo.png" width="200px" height="250px">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <h2>Nattawat Sommit</h2>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
