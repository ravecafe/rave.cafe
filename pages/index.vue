<template>
  <div class="container">
    <div class="img-wrap">
      <NuxtLink to="/welcome">
        <Logo height="200" />
      </NuxtLink>
    </div>
  </div>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: #212121;
  background-size: 130% 130%;
  background-position: center;
  overflow: hidden;
}

.img-wrap {
  width: 100%;
}

@keyframes Gradient {
  0% {
    background-position: 51% 0%;
  }
  50% {
    background-position: 50% 100%;
  }
  100% {
    background-position: 51% 0%;
  }
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 30px;
  color: var(--black);
  letter-spacing: 1px;
  mix-blend-mode: difference;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
