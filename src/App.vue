<template>
  <h2>vue3 web app</h2>
  <img src="./assets/images/vue.png"/>
</template>
<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  name: 'App',
})
</script>
<style scoped lang="less" rel="stylesheet/less">
@import "./assets/less/app.less";
h2 {
  font-weight: bold;
  text-align: center;
  margin-top: 150px;
}
img{
  display: block;
  margin: 0 auto;
}
</style>
