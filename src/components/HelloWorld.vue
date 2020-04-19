<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'HelloWorld',
  props: {
    msg: String,
  },
});
</script>

<style scoped lang="scss">
h1 {
  color: black;
  font-family: Abril Fatface;
  font-size: 65px;
}
a {
  color: #42b983;
}
</style>
