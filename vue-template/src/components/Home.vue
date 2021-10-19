<template>
  <div id="home">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: "Home",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
#home {
  max-width: 30rem;
}
</style>
