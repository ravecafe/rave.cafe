<template>
  <section class="menu">
    <h1>menu</h1>
    <h3 class="menu-title">bevs</h3>
    <ul>
      <li><NuxtLink to="/menu/coffee">coffee</NuxtLink></li>
      <li>butter coffee</li>
      <li>iced tea</li>
      <li>lemon seltz</li>
    </ul>
    <h3 class="menu-title">food</h3>
    <ul class="food-list">
      <li>
        <p>fish tin</p>
        &
        <p>herbed veggies</p>
        &
        <p>sweet potato / plantain mash</p>
      </li>
      <li>
        <p>soft boiled eggs</p>
        &
        <p>coconut greens</p>
        &
        <p>seaweed rice</p>
      </li>
      <li>iced weed</li>
    </ul>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.menu {
  display: flex;
  max-width: 700px;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
  flex-direction: column;
}

.menu-title {
  font-size: 40px;
  margin: 20px 0;
}

h1 {
  font-size: 55px;
}

ul {
  text-align: center;
}

li {
  margin: 10px 0 10px;
}

a {
  color: #fff;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

.food-list li {
  margin: 0 0 50px 0;
}
</style>
