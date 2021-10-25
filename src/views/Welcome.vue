<template>
  <h1>Welcome Page</h1>
  <LoginForm />
  <SignupForm />
</template>

<script>
import LoginForm from "../components/LoginForm.vue";
import SignupForm from "../components/SignupForm.vue";
export default {
  components: { LoginForm, SignupForm },
  setup() {},
};
</script>

<style></style>
