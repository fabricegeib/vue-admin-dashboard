<template>
  <div class="home">
    <Header />
    <img alt="Vue logo" src="../assets/logo.png" />
    <FirstComponent msg="My first Vue.js view with props" />
  </div>
</template>

<script>
// @ is an alias to /src
import FirstComponent from "@/components/FirstComponent.vue";
import Header from "@/components/Header.vue";


export default {
  name: "Firstiew",
  components: {
    FirstComponent,
    Header
  }
};
</script>
