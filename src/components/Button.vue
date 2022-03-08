<template>
  <button class="tchoin"><slot /></button>
</template>

<script>
export default {};
</script>

<style scoped>
.tchoin {
  color: #212121;
  background-color: white;
}

.tchoin:hover {
  color: white;
  background-color: #212121;
}
</style>
