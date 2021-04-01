<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <h1 class="name">lkx</h1>
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
</template>

<script lang="ts">
import HelloWorld from '/@/components/HelloWorld.vue'
import '/@/assets/app.css'
import data from '/@/assets/lkx.json'
const lkx: string = 'lkx~'
export default {
  name: 'App',
  components: {
    HelloWorld
  },
  mounted() {
    console.log(lkx)
    console.log(data.name + data.age)
  }
}
</script>

<style lang="scss">
  .name{
    color:green;
  }
</style>
