<template>
  <section class="container">
    <h1 class="title">music</h1>
    <ul>
      <li><NuxtLink to="/music/001" class="mix-link">001: L&D </NuxtLink></li>
    </ul>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.mix-link {
  color: #fff;
  text-decoration: none;
  font-size: 50px;
}

.mix-link:hover {
  text-decoration: underline;
}
</style>
