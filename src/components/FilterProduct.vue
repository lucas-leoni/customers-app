<template>
  <div class="filter">
      <label for="produto">Produto | {{product}} <br>
      <input
        type="text"
        v-model="product"
        placeholder="Informe um produto">
      </label>
  </div>
</template>

<script>
export default {
  name: 'FilterProduct',
  data() {
    return {
      product: '',
    };
  },
};
</script>
<style scoped>
.filter {
    margin-top: 10px;
    margin-bottom: 10px;
}
</style>
