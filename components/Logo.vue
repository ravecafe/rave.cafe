<template>
  <div>
    <NuxtLink to="/welcome">
      <img class="logo" src="~/assets/rave.cafe.png" alt="rave.cafe logo" />
    </NuxtLink>
  </div>
</template>

<style>
.logo {
  animation: 15s rotation infinite linear;
  margin: auto;
  opacity: 0.4;
  height: 300px;
  filter: blur(4px);
  transition: all 2s ease;
}

.logo:hover {
  filter: blur(0px);
  opacity: 0.6;
  transition: all 2s ease;
}

@keyframes rotation {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(-359deg);
  }
}
</style>
