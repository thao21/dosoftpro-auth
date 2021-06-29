<template>
  <main>
    <section class="warehouse-wrapper">
      <form id="table-user">
        <div class="table-header">
          <nav-bar />
        </div>
        <div class="table-content">
          <div class="container-fluid">
            <product-list />
            <footer-bar />
          </div>
        </div>
      </form>
  </section>
  </main>
</template>

<script>
import NavBar from '../components/NavBar.vue';
import ProductList from '../components/ProductList.vue';
import FooterBar from '../components/FooterBar.vue';

export default {
  name: "Home",
  components: {
    NavBar,
    ProductList,
    FooterBar,
  },
};
</script>
