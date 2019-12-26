<template>
    <div class="sign-in container">
        <div class="login">
            <!-- <h1>Sign In</h1> -->
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

.login {
    height: 50px;
    width: 50px;
    background-color: $light-gray;
}
</style>