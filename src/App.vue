<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import "@/assets/global-styles/colors.scss";
@import "@/assets/global-styles/typography.scss";

body {
  background-color: $dark-blue;
  margin: 0;
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  // color: #2c3e50;
  color: $white;
}

// h1 {
//   @include heading-3;
// }

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    // color: #2c3e50;
    color: $white;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
