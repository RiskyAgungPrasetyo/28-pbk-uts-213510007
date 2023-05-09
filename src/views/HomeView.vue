<template>
  <div class="home">
    <h1>WELCOME TO OUR WEBSITE</h1>
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
<style>
.home{
  color: white;
}
</style>