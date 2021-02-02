<template>
  <section class="container">
    <h1 class="mu-title">music</h1>
    <ul>
      <li class="mix-link">001: <NuxtLink to="/music/001">L&D </NuxtLink></li>
    </ul>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.mu-title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: normal;
  font-size: 80px;
  color: #fff;
  width: 100%;
  border-bottom: 1px solid #fff;
  letter-spacing: 1px;
  mix-blend-mode: difference;
  padding: 20px;
  margin-bottom: 20px;
}
.mix-link {
  color: #fff;
  text-decoration: none;
  font-size: 50px;
}

a:hover {
  text-decoration: underline;
}
</style>
