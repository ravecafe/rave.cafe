<template>
  <section class="threshold">
    <h1 class="mu-title">001: L&D</h1>
    <img class="header-img" src="~/assets/001/000162310027.jpg" />
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
      <h3>Crossing of the Return Threshold</h3>
      <p>
        "Many failures attest to the difficulties of this life-affirmative
        threshold. The first problem of the returning hero is to accept as real,
        after an experience of the soul-satisfying vision of fulfillment, the
        passing joys and sorrows, banalities and noisy obscenities of life. Why
        re-enter such a world? Why attempt to make plausible, or even
        interesting, to men and women consumed with passion, the experience of
        transcendental bliss? As dreams that were momentous by night may seem
        simply silly in the light of day, so the poet and the prophet can
        discover themselves playing the idiot before a jury of sober eyes. The
        easy thing is to commit the whole community to the devil and retire
        again into the heavenly rock dwelling, close the door, and make it fast.
        But if some spiritual obstetrician has drawn the shimenawa across the
        retreat, then the work of representing eternity in time, and perceiving
        in time eternity, cannot be avoided."
        <br />
        <br />
        -
        <a
          href="https://en.wikipedia.org/wiki/Hero's_journey#The_Crossing_of_the_Return_Threshold"
          >Joseph Campbell</a
        >
      </p>

      <img src="~/assets/001/IMG_1076.JPG" />
      <p>
        Recorded on 12.29.20 on 2x XDJ-700s and a Xone 23
        <br />
        <br />
        We played a set at Dark Matter Immersive's Garden of Eden installation
        at the cell. The installation is based around Joseph Campbell's The
        Hero's Journey. The exhibition itself and 2020 were coming to a close so
        we focused our energy on the moment in which one arrives back to
        integrate the wisdom gained on the journey - the return threshold. How
        do we reintegrate the wisdom we gain each day?
      </p>
      <img src="~/assets/001/IMG_1075.JPG" />
      <img src="~/assets/001/000162310029.jpg" />
      <p>
        Being is breathing,
        <br />
        each day
        <br />
        is a threshold of becoming.
        <br />
        The choices we make
        <br />
        ripple ever outward.
        <br />
        What fulfills you?
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

.header-img {
  margin: 50px 0;
}

.mu-title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: normal;
  font-size: 80px;
  color: #fff;
  width: 80%;
  letter-spacing: 1px;
  mix-blend-mode: difference;
  padding: 20px;
  margin-bottom: 20px;
  text-align: center;
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
}

h3 {
  font-size: 40px;
  text-align: center;
  margin: 10% 0 5%;
}

img {
  width: 100%;
  margin: 5% 0;
}
</style>
