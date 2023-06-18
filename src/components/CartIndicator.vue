<template>
  <router-link class="header__cart"  aria-label="Корзина с товарами" :to="{name: 'cart'}">
    <svg width="30" height="21" fill="currentColor">
      <use xlink:href="#icon-cart"></use>
    </svg>
    <span class="header__count" aria-label="Количество товаров">3</span>
  </router-link>
</template>
<script>
export default {

};
</script>
