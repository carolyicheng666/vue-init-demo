<style scoped lang="less">
.index {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 200px;
  border: 1px solid #ccc;
  & span {
    font-size: 32px;
    font-weight: bold;
    color: #f00;
  }
}
</style>
<template>
  <div class="index">
    <span>index</span>
  </div>
</template>
<script>
export default {
}
</script>