<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/surfing_pic.png">
    <HelloWorld msg="Surfing in Beautiful Tahiti"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
