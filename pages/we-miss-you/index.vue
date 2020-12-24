<template>
  <section class="container">
    <h1 class="title-right">we miss you</h1>
    <div class="logo-wrap">
      <Logo height="50" />
    </div>
    <p>
      we miss you, we are thinking of you, and we are very grateful to have you
      in our lives. here are some moments that have been significant to us in
      2020. we hope they also bring you joy!
    </p>
    <p class="center">&lt;3</p>
    <p>
      we are exploring new ways of staying connected outside of social media.
      drop your email below if you'd like to learn more about
      <a href="https://rave.cafe">rave.cafe</a> &amp; receive january's menu
    </p>
    <p class="center">L&amp;D</p>
    <iframe
      width="100%"
      height="166"
      scrolling="no"
      frameborder="no"
      allow="autoplay"
      src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/953332642&color=%232c2c2c&auto_play=false&hide_related=true&show_comments=false&show_user=true&show_reposts=false&show_teaser=false"
    ></iframe>
    <div
      style="
        font-size: 10px;
        color: #cccccc;
        line-break: anywhere;
        word-break: normal;
        overflow: hidden;
        white-space: nowrap;
        text-overflow: ellipsis;
        font-family: Interstate, Lucida Grande, Lucida Sans Unicode, Lucida Sans,
          Garuda, Verdana, Tahoma, sans-serif;
        font-weight: 100;
      "
    >
      <a
        href="https://soundcloud.com/ravecafe"
        title="rave.cafe"
        target="_blank"
        style="color: #cccccc; text-decoration: none"
        >rave.cafe</a
      >
      ·
      <a
        href="https://soundcloud.com/ravecafe/ld-2020cafe"
        title="L&amp;D - 2020"
        target="_blank"
        style="color: #cccccc; text-decoration: none"
        >L&amp;D - 2020</a
      >
    </div>
    <section class="month-cell">
      <h2>01 - january</h2>
      <p>Val Young - Seduction</p>
      <img src="~/assets/miss-u/01/000206700019.jpg" />
      <img
        class="vertical"
        src="~/assets/miss-u/01/A7238C14-B2D0-424C-A47E-E26427D3EB62.jpeg"
      />
      <p>we love you mood ring</p>
      <img
        src="~/assets/miss-u/01/10210662-9598-4D15-8668-E660C43F9555_1_105_c.jpeg"
      />
      <p>
        "the world's loudest photo" 35mm, taken during a serene moment at
        ambient church
      </p>
      <img src="~/assets/miss-u/01/000065770010.869265a.jpg" />
      <p>foreshadowing</p>
    </section>
    <section class="month-cell">
      <h2>02 - february</h2>
    </section>
    <section class="month-cell">
      <h2>03 - march</h2>
    </section>
    <section class="month-cell">
      <h2>04 - april</h2>
    </section>
    <section class="month-cell">
      <h2>05 - may</h2>
    </section>
    <section class="month-cell">
      <h2>06 - june</h2>
    </section>
    <section class="month-cell">
      <h2>07 - july</h2>
    </section>
    <section class="month-cell">
      <h2>08 - august</h2>
      <video muted autoplay class="media-center">
        <source
          src="https://media.giphy.com/media/XETrg0yyG3jOYrADq9/giphy.mp4"
          type="video/mp4"
        />
      </video>
    </section>
    <section class="month-cell">
      <h2>09 - september</h2>
    </section>
    <section class="month-cell">
      <h2>10 - october</h2>
    </section>
    <section class="month-cell">
      <h2>11 - november</h2>
    </section>
    <section class="month-cell">
      <h2>12 - december</h2>
    </section>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.title-right {
  text-align: right;
  margin: 20px 0 0;
}
p {
  margin: 10px 0;
}
.center {
  text-align: center;
}
a {
  color: #fff;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
.logo-wrap {
  margin: 5% auto 0;
}
.container {
  display: flex;
  max-width: 700px;
  align-items: center;
  justify-content: center;

  margin: 0 auto;
  flex-direction: column;
  font-size: 1.25rem;
}
.month-cell {
  margin: 5% 0;
}
.month-cell img {
  width: 100%;
  height: auto;
  margin: 5% 0;
}
.month-cell h2,
h1 {
  margin: 3% 0;
  font-size: 2.25rem;
}
.month-cell p {
  margin: 2% 10% 2% 0;
  font-size: 1.25rem;
}
@media only screen and (max-width: 850px) {
  .container {
    margin: 0 auto;
    max-width: 400px;
  }
}
@media only screen and (max-width: 500px) {
  .container {
    margin: 0 10%;
  }
}
</style>
