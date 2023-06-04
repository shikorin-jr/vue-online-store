<template>
  <ul class="catalog__list">
    <ProductItem v-for="(product, index) in products" :product="product" :key="index" />
  </ul>
</template>

<script>
import ProductItem from '@/components/ProductItem.vue';

export default {
  components: { ProductItem },
  props: ['products'],
};
</script>
