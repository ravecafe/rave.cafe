<template>
  <section class="welcome">
    <nav>
      <ul>
        <li>
          <NuxtLink to="/menu">menu</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/music">music</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/garden">garden</NuxtLink>
        </li>
      </ul>
    </nav>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  font-size: 80px;
  height: 99vh;
  overflow: hidden;
}
a {
  color: #fff;
  text-decoration: none;
}

a:hover {
  text-decoration: none;
}
.welcome {
  color: #fff;
}
</style>
