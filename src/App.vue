<template>
  <div id="app">
    <my-add></my-add>
    <p>-------------华丽的分割线---------------</p>
    <my-sub></my-sub>
  </div>
</template>
<script>
//导入组件
import Add from './components/Add'
import Sub from './components/Sub'
export default {
  data() {
    return {}
  },
  components: {
    'my-add': Add,
    'my-sub': Sub
  }
}
</script>
<style></style>
