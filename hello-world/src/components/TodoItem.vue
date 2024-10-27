<script>
export default {
  name: "TodoItem",
  data() {
    return {
      checked: false
    };
  }
};
</script>

<template>
  <!-- `checked` 为 true 或 false -->
  <div>
    <el-checkbox v-model="checked" class="checkbox-item">洗衣服</el-checkbox>
  </div>
</template>

<style scoped>
.checkbox-item {
  display: block; /* 块级元素 */
  margin-bottom: 10px; /* 若有需要，可以调整间距 */
}
</style>


