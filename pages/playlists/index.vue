<template>
  <section class="container">
    <h1 class="mu-title">playlists</h1>
    <ul class="playlist-grid">
      <li class="mix-link">
        <iframe
          src="https://www.buymusic.club/embed/ravecafe-circle-with-upper-right-quadrantlower-half-circlecircle-with-upper-right-quadrant-001-landd"
          height="500"
          width="100%"
          frameborder="0"
        ></iframe>
      </li>
      <li class="mix-link">
        <iframe
          src="https://www.buymusic.club/embed/ravecafe-circle-with-upper-right-quadrantlower-half-circlecircle-with-upper-right-quadrant-002-welcome-to-the-cafe"
          height="500"
          width="100%"
          frameborder="0"
        ></iframe>
      </li>
    </ul>
    <NuxtLink to="/welcome" class="footer">
      <Logo height="30" />
    </NuxtLink>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.playlist-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  /* grid-column-gap: 20px;
  grid-row-gap: 20px; */
}

.playlist-grid h3 {
  margin-bottom: 10px;
}

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

.footer {
  margin: 20px 0;
}

@media only screen and (max-width: 850px) {
  .playlist-grid {
    grid-template-columns: repeat(1, 1fr);
  }
}
</style>
