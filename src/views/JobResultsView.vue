<template>
  <h1 class="text-6xl font-bold">Job Results page</h1>
  <button @click="gotToHome">Go to Home Page</button>
</template>

<script>
export default {
  name: "JobResultsView",
  methods: {
    gotToHome() {
      this.$router.push({ name: "Home" });
    },
  },
};
</script>
