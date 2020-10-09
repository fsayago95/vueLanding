<template>
  <div class="gral">
    <div class="container-header">
      <h1>Features</h1>
      <h1>Screenshot</h1>
      <h1>Testimonials</h1>
      <h1>Pricing</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.gral {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
}
.container-header {
  display: flex;
  justify-content: flex-end;
}

h1 {
  margin: 10px;
  font-size: 18px;
  line-height: 21px;
}
</style>
