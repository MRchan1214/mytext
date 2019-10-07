<template>
  <div id="app">
    <h1>这是app根组件</h1>
    <index></index>
    <router-view />
  </div>
</template>

<script>
import index from './views/index'
export default {
  components: {
    index: index
  }
}
</script>
<style lang="less">
</style>
