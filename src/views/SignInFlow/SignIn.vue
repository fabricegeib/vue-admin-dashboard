<template>
  <div class="container">
    <div class="request">Don’t have an account ?
      <router-link to="/request">Request an account</router-link>
    </div>
    <div class="login">
      <img src="@/assets/img/iamfabriceg-avatar-border.png">
      <h4>Sign into iamfabriceg.xyz</h4>
      <input type="email" placeholder="Email">
      <input type="password" placeholder="Password">
      <button>Sign In</button>
      <router-link to="/recover">Forgot your password ?</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "SignIn"
}
</script>

<style scoped lang="scss">
@import "@/assets/global-styles/colors.scss";
@import "@/assets/global-styles/typography.scss";

.container {
  display: flex;
  justify-content: center;
  align-items: center;

  min-height: 100vh;
}

.request {
  position: absolute;

  top: 40px;
  right: 40px;

  color: rgba(255, 255, 255, 0.3);
  a {
      color: $white;
  }
}

.login {
  width: 400px;
}

img {
  max-width: 180px;
  width: 50%;
  height: auto;
}

h4 {
  margin: 0;
  line-height: 34px;
  font-size: 24px;
  text-align: center;

  color: $white;
}

input {
  background: rgba(255, 255, 255, 0.2);
  border: 1px solid rgba(255, 255, 255, 0.2);
  box-sizing: border-box;
  border-radius: 4px;

  height: 60px;
  width: 100%;

  color: $white;
  font-size: 20px;
  padding-left: 20px;
  margin-top: 20px;

  &::placeholder {
    color: rgba(255, 255, 255, 0.3);
  }
}

button {
  background: #56CCF2;
  box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.2);
  border-radius: 4px;
  border: none;

  height: 60px;
  width: 100%;

  color: $white;
  font-size: 20px;
  margin-top: 20px;
  margin-bottom: 40px;
}

a {
  font-size: 16px;
  line-height: 25px;
  text-align: center;
  text-decoration: none;

  color: rgba(255, 255, 255, 0.3);
}
</style>