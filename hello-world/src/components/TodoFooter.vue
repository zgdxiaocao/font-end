<script>
export default {
  name: "TodoFooter",
  data() {
    return {
      checked: false
    };
  }
}
</script>

<template>
  <!-- `checked` 为 true 或 false -->
  <div>
    <el-checkbox v-model="checked">已完成0/全部</el-checkbox>
  </div>
</template>

<style scoped>

</style>
