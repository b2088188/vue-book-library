<template>
  <header class="header">
    <!--     <GoogleAuth /> -->
    <SearchForm />
    <nav class="nav">
      <ul class="nav__list">
        <!-- <ShoppingCart />
                             <BookMarks /> -->
      </ul>
    </nav>
  </header>
</template>

<script>
import SearchForm from "@/views/header/SearchForm";
export default {
  name: "Header",
  components: {
    SearchForm,
  },
};
</script>

<style lang="scss" scoped>
.header {
  height: 10rem;
  display: flex;
  position: relative;
}
.nav {
  -ms-grid-row-align: stretch;
  align-self: stretch;

  &__list {
    list-style: none;
    display: flex;
    height: 100%;
  }
}
</style>
