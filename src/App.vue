<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
  @import "~@/assets/style/helper.scss";
  @import "~@/assets/style/reset.scss";
  body {
    max-width: 400px;
    margin: 0 auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #333;
    font-family: $font-hei;
    font-size: 16px;
    line-height: 1.5;
    background: #F5F5F5;
  }
</style>
