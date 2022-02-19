<template>
<div>第一次  哦</div>
<div v-for="item in 10" :key="item">{{item}}</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
