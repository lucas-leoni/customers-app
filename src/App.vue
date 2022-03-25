<template>
  <div id="app">
    Lista de Clientes
    <FilterProduct v-if="false"/>
    <CardProducts />
    <Person />
  </div>
</template>
<script>
import CardProducts from '@/components/Card.vue';
import FilterProduct from '@/components/FilterProduct.vue';
import Person from '@/components/Person.vue';

export default {
  name: 'App',
  components: {
    CardProducts,
    FilterProduct,
    Person,
  },
};
</script>
