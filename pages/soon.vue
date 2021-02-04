<template>
  <section class="soon">
    <h1>soon</h1>
    <NuxtLink to="/welcome">
      <Logo height="30" />
    </NuxtLink>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.soon {
  display: flex;
  max-width: 700px;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
  flex-direction: column;
  text-align: center;
  height: 100vh;
}
h1 {
  margin-bottom: 40px;
}
</style>
