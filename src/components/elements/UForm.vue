<template>
  <div class="form-wrapper">
    <form class="form">
      <input-ui />
    </form>
  </div>
</template>

<script>
import InputUi from "@/components/ui/UInput.vue";

export default {
  components: {
    InputUi,
  },
};
</script>

<style lang="scss" scoped>
.form-wrapper {
  width: 100%;
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>