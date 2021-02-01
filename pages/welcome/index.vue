<template>
  <section class="welcome">
    <nav>
      <ul>
        <li>
          <NuxtLink to="/soon">menu</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/music">music</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/soon">garden</NuxtLink>
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
  padding: 10% 0;
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
  transition: filter 500ms ease;
}

a:hover {
  text-decoration: none;
  filter: blur(10px);
  transition: filter 500ms ease;
}
.welcome {
  color: #fff;
  background: radial-gradient(#212121, #222222, #1c1c1c, #131313);
  background-size: 150% 130%;
  background-position: center;
  overflow: hidden;
}
</style>
