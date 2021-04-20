<template>
  <section class="container">
    <h1 class="mu-title">mixes</h1>
    <ul>
      <li class="mix-link">
        <sup>001</sup> <NuxtLink to="/mixes/001">L&D </NuxtLink>
      </li>
      <li class="mix-link">
        <sup>002</sup> <NuxtLink to="/mixes/002">welcome 2 the cafe </NuxtLink>
      </li>
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

.mix-link sup {
  font-size: 25px;
}

a:hover {
  text-decoration: underline;
}

@media only screen and (max-width: 700px) {
  .mix-link {
    color: #fff;
    text-decoration: none;
    font-size: 25px;
  }
  .mix-link sup {
    font-size: 18px;
  }
}
</style>
