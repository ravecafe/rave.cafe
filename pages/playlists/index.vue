<template>
  <section class="container">
    <h1 class="mu-title">playlists</h1>
    <div class="playlist-grid">
      <section>
        <h3>001 - en3rgy</h3>
        <iframe
          src="https://open.spotify.com/embed/playlist/3pjWSnVMwgSU2zZo5RcRbQ"
          width="400"
          height="365"
          frameborder="0"
          allowtransparency="true"
          allow="encrypted-media"
        ></iframe>
      </section>
      <section>
        <h3>002 - you ar3 here</h3>
        <iframe
          src="https://open.spotify.com/embed/playlist/7zMpwlXpDQ8MJVuhzua1Hq"
          width="100%"
          height="365"
          frameborder="0"
          allowtransparency="true"
          allow="encrypted-media"
        ></iframe>
      </section>
      <section>
        <h3>003 - the futur3 is bright</h3>
        <iframe
          src="https://open.spotify.com/embed/playlist/3Wnh0LOILg6cE6yh1VHrhl"
          width="100%"
          height="365"
          frameborder="0"
          allowtransparency="true"
          allow="encrypted-media"
        ></iframe>
      </section>
      <section>
        <h3>004 - cyb0rg</h3>
        <iframe
          src="https://open.spotify.com/embed/playlist/5GG9VSyqpAVgaN7KjPf5Vp"
          width="100%"
          height="365"
          frameborder="0"
          allowtransparency="true"
          allow="encrypted-media"
        ></iframe>
      </section>
      <section>
        <h3>005 - bre@ks</h3>
        <iframe
          src="https://open.spotify.com/embed/playlist/4HWdstRLiqAI3UhhJqNet3"
          width="100%"
          height="365"
          frameborder="0"
          allowtransparency="true"
          allow="encrypted-media"
        ></iframe>
      </section>
      <section>
        <h3>006 - flo4ting</h3>
        <iframe
          src="https://open.spotify.com/embed/playlist/4UQ8FcO7DVvBDZNkWZhTZX"
          width="100%"
          height="365"
          frameborder="0"
          allowtransparency="true"
          allow="encrypted-media"
        ></iframe>
      </section>
      <section>
        <h3>007 - ᴠ0ᴄᴀʟꜱ</h3>
        <iframe
          src="https://open.spotify.com/embed/playlist/0hfsJTfmhxhVDyI3AHJLfE"
          width="100%"
          height="365"
          frameborder="0"
          allowtransparency="true"
          allow="encrypted-media"
        ></iframe>
      </section>
      <section>
        <h3>008 - ᴄʜᴜʙʙʏ ꜰᴜɴᴋ</h3>
        <iframe
          src="https://open.spotify.com/embed/playlist/5HYMzvn16Min60GSn3cVd5"
          width="100%"
          height="365"
          frameborder="0"
          allowtransparency="true"
          allow="encrypted-media"
        ></iframe>
      </section>
    </div>
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
  grid-column-gap: 20px;
  grid-row-gap: 20px;
}

.playlist-grid > iframe {
  width: 100%;
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
