<template>
  <div class="grid">
    <div class="block">
      <span>Standard</span>
    </div>
    <div class="block">
      <span>Primary</span>
    </div>
    <div class="block">
      <span>Outline</span>
    </div>
    <div class="block">
      <span>Link/Text</span>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.grid {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  padding: 40px;
}
</style>