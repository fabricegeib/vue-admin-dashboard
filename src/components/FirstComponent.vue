<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>FirstComponent</p>
  </div>
</template>

<script>
export default {
  name: "FirstComponent",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
