<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=DM+Sans&display=swap');
:root {
  --black: #1c1c1c;
}
html {
  font-family: 'DM Sans', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  color: #fff;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

body {
  background-color: var(--black);
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

a {
  color: #fff;
  text-decoration: none;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: radial-gradient(#212121, #222222, #1c1c1c, #131313);
  background-size: 130% 130%;
  background-position: center;
  overflow: hidden;
}

h1 {
  font-size: 55px;
}
</style>
