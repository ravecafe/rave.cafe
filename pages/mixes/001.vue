<template>
  <section class="threshold">
    <h1 class="mu-title"><sup>001</sup> L&D</h1>
    <img class="header-img" src="~/assets/welcome/mix001.jpg" />
    <section class="player">
      <iframe
        width="100%"
        height="166"
        scrolling="no"
        frameborder="no"
        allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1003785298&color=%232c2c2c&auto_play=false&hide_related=true&show_comments=false&show_user=true&show_reposts=false&show_teaser=false"
      ></iframe>
    </section>
    <section class="photos">
      <p>
        We streamed this set on 12.29.20 at
        <a href="https://www.instagram.com/darkmatterimmersive/"
          >Dark Matter Immersive</a
        >'s Garden of Eden installation at the cell.
      </p>
      <p>
        The isolation of the past year resulting from a global pandemic that
        accelerated the fissures of a system built on white supermacy,
        individualism, and extraction has led us to go deep within ourselves. We
        are one with nature and not separate from it. We manifest our reality
        through our thoughts which respond to our environment. Our nature is
        limitless when we point ourselves toward a beginner's mind where
        learning and living your truth is celebrated. Processing your pain and
        facing your fear is vital to unlocking your inherent creative, joyful
        self. <br />
        All is mind.
      </p>
    </section>
    <NuxtLink to="/welcome">
      <Logo height="30" />
    </NuxtLink>
    <br />
    <br />
    <br />
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.threshold {
  padding-top: 5%;
  width: 80%;
  margin: 0 auto;
  max-width: 900px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

a {
  text-decoration: underline;
}

.header-img {
  margin: 50px 0;
}

.mu-title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: normal;
  font-size: 60px;
  color: #fff;
  width: 950%;
  letter-spacing: 1px;
  mix-blend-mode: difference;
  padding: 20px;
  margin-bottom: 20px;
  text-align: center;
}

.mu-title sup {
  font-size: 25px;
}

.threshold p {
  margin: 5% auto;
  max-width: 500px;
}

.center {
  text-align: center;
}

.photos {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-bottom: 10%;
  margin-top: 4%;
}

.player {
  display: flex;
  justify-content: center;
  width: 80%;
}

h3 {
  font-size: 40px;
  text-align: center;
  margin: 10% 0 5%;
}

img {
  width: 100%;
  margin: 5% 0;
  transition: opacity 5s ease-out;
}
@media only screen and (max-width: 700px) {
  .mu-title {
    color: #fff;
    text-decoration: none;
    font-size: 25px;
    padding: 10px;
    margin-bottom: 5px;
  }
  .mu-title sup {
    font-size: 18px;
  }
}
</style>
