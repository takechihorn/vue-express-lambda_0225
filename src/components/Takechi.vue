<template>
  <div>
    <h1>Hello from Takechi Component</h1>
    <h2>Tests 1223</h2>
    <h3>{{ world }}</h3>
  </div>
</template>

<script>
export default {
  data: () => ({
    world: "Hello World",
  }),
};
</script>

<style>
</style>

<style lang="scss" scoped>
h1 {
  color: blue;
}
</style>
