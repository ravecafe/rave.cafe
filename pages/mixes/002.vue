<template>
  <section class="threshold">
    <h1 class="mu-title"><sup>002</sup> welcome 2 the cafe</h1>
    <img class="header-img" src="~/assets/welcome/welcome.jpg" />
    <section class="player">
      <iframe
        width="100%"
        height="166"
        scrolling="no"
        frameborder="no"
        allow="autoplay"
        src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1032948211&color=%232c2c2c&auto_play=false&hide_related=true&show_comments=false&show_user=true&show_reposts=false&show_teaser=false"
      ></iframe>
    </section>
    <section>
      <p>
        rave.cafe is an iterative digital art project intended to be an
        extension of conversations & collaborations with friends, and an
        expression of the family we've found on the dance floor.
      </p>
      <p>
        we are experimenting with different ways of presenting music, connecting
        outside of social media, and playing around with the internet as a
        canvas.
      </p>
      <p>
        the site will feature a variety of mixes, playlists, & conversations
        with DJs, producers, & artists. to kick it off we've asked some of our
        friends to help us put together a radio mix of the one track they are
        most excited to share with the world right now alongside a buy music
        club playlist of artists they want to support. it has always been our
        intention that this project grow and develop through collaboration so
        feel free to let us know if you have thoughts
        <a href="mailto:hey@rave.cafe">hey@rave.cafe</a>
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
  margin: 40px 0;
}

.mu-title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: normal;
  font-size: 60px;
  color: #fff;
  width: 100%;
  letter-spacing: 1px;
  mix-blend-mode: difference;
  padding: 20px;
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
}

.player {
  display: flex;
  justify-content: center;
  width: 80%;
  margin: 5% 0;
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
@media only screen and (max-width: 750px) {
  .mu-title {
    color: #fff;
    text-decoration: none;
    font-size: 25px;
    padding: 10px;
    margin-top: 10px;
  }
  .mu-title sup {
    font-size: 18px;
  }
}
</style>
