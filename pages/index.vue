<template>
  <main>
    <h1>Hello World</h1>
  </main>
</template>

<style lang="scss" scoped>
  @import "~static/style/grid.scss";

  h1 {
    color: red;
    @include breakpoint(mdl) {
      color: blue;
    }
  }
</style>

<script>
  export default {}
</script>
