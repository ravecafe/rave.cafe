<template>
  <div>
    <NuxtLink to="/welcome">
      <img
        class="logo"
        :style="style"
        src="~/assets/rave.cafe.png"
        alt="rave.cafe logo"
      />
    </NuxtLink>
  </div>
</template>

<script>
export default {
  name: 'Logo',
  props: {
    height: {
      type: Number,
      default: 100,
    },
  },
  computed: {
    style() {
      return `height: ${this.height}px;`
    },
  },
}
</script>

<style>
.logo {
  animation: 15s rotation infinite linear;
  margin: auto;
  opacity: 0.2;
  transition: all 2s ease;
}

.logo:hover {
  opacity: 0.7;
  transition: opacity 1s ease;
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
