<template>
  <div class="card">
    <h1>Card Componente</h1>
    <!-- <p>{{ name }}</p>
    <p>{{ description }}</p> -->
    <p>{{ person }}</p>
  </div>
</template>
<script>
export default {
  name: 'CardProducts',
  props: {
    person: {
      type: Object,
      // required: true,
    },
  },
  data() {
    return {
      // name: 'Notebook',
      // description: 'Corei5, 2.6ghz, 8gb, tela widescreen 15,4',
    };
  },
};
</script>
<style scoped>
.card {
  max-width: 400px;
  height: 200px;
  padding: 10px;
  background-color: #eee;
  border: 1px solid #999;
  color: black;
}
h1 {
  color: blue;
}
</style>
