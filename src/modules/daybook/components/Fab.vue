<template>
  <div id="btn-plus">
    <button class="btb btn-primary">
      <i class="fas fa-2x" :class="icon"></i>
    </button>
  </div>
</template>

<script>
export default {
  name: "btn-plus",
  props: {
    icon: {
      type: String,
      default: "fa-plus",
    },
  },
};
</script>

<style lang="scss" scoped>
button {
  position: fixed;
  bottom: 20px;
  right: 20px;
  width: 80px;
  height: 80px;
  border-radius: 100%;
}
</style>