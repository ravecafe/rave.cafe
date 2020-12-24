<template>
  <section class="menu">
    <NuxtLink to="/menu"><h1>menu</h1></NuxtLink>
    <h3 class="menu-title">coffee</h3>
    <h5 class="menu-sub">hot</h5>
    <ul>
      <li>choose quality, freshly roasted beans</li>
      <li>boil water</li>
      <li>grind to the desired consistency</li>
      <li>add to brewing method</li>
      <li class="tooltip">
        bloom coffee <br /><span class="tooltiptext"
          >dampen with water and let the gases release for 30-40 seconds</span
        >
      </li>
      <li>continue brewing & enjoy</li>
    </ul>
    <h3 class="menu-title">+ butter & mct</h3>
    <ul>
      <li>
        blend with 1-2 tbsp of grass-fed butter & 1 tsp - 1tbsp of MCT oil
      </li>
      <li>continue brewing & enjoy</li>
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

.menu-sub {
  font-size: 32px;
}

ul {
  text-align: center;
}

li {
  margin: 10px 0 10px;
}
.tooltip {
  position: relative;
}

.tooltip .tooltiptext {
  visibility: hidden;
  width: 100%;
  background: radial-gradient(#212121, #222222, #1c1c1c, #131313);
  color: #fff;
  text-align: center;
  border-radius: 10px;
  padding: 5%;
  border: 1px solid rgb(52, 52, 52);

  /* Position the tooltip */
  position: absolute;
  z-index: 1;
  left: 0;
  opacity: 0;
  top: 0;
  transition: all 400ms ease;
}

.tooltip:hover .tooltiptext {
  visibility: visible;
  cursor: help;
  opacity: 1;
  transition: all 400ms ease;
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
