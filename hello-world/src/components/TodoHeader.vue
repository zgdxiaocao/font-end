<!--TodoList的头部-->
<script>
export default {
  name: "TodoHeader",
  data() {
    return {
      input: ''
    }
  }
}
</script>

<template>
  <div>
    <el-input v-model="input" placeholder="请输入内容"></el-input>
  </div>
</template>

<style scoped>

</style>
