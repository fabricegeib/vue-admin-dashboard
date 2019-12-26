<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <FirstComponent msg="My first Vue.js view with props" />
  </div>
</template>

<script>
// @ is an alias to /src
import FirstComponent from "@/components/FirstComponent.vue";

export default {
  name: "Firstiew",
  components: {
    FirstComponent
  }
};
</script>
