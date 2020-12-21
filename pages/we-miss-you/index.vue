<template>
  <section class="container">
    <h1>we miss you</h1>
    <Logo height="50" />
    <p>
      we wanted to put together a snapshot of our year and share it with all of
      you
    </p>
    <section class="month-cell">
      <h2>january</h2>
      <img src="~/assets/filler.jpg" />
      <p>
        yurr i get turnt up. we wanted to. we wanted to put together a snapshot
        of our year and share it with all of you put together a snapshot of our
        year and share it with all of you yurr i get turnt up. we wanted to. we
        wanted to put together a snapshot of our year and share it with all of
        you put together a snapshot of our year and share it with all of you
      </p>
      <p>Val Young - Seduction</p>
    </section>
    <section class="month-cell">
      <h2>february</h2>
      <img src="~/assets/filler.jpg" />
      <p>
        yurr i get turnt up. we wanted to. we wanted to put together a snapshot
        of our year and share it with all of you put together a snapshot of our
        year and share it with all of you yurr i get turnt up. we wanted to. we
        wanted to put together a snapshot of our year and share it with all of
        you put together a snapshot of our year and share it with all of you
      </p>
      <p>Val Young - Seduction</p>
    </section>
    <section class="month-cell">
      <h2>march</h2>
      <img src="~/assets/filler.jpg" />
      <p>
        yurr i get turnt up. we wanted to. we wanted to put together a snapshot
        of our year and share it with all of you put together a snapshot of our
        year and share it with all of you yurr i get turnt up. we wanted to. we
        wanted to put together a snapshot of our year and share it with all of
        you put together a snapshot of our year and share it with all of you
      </p>
      <p>Val Young - Seduction</p>
    </section>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  display: flex;
  max-width: 800px;
  /* align-items: center; */
  justify-content: center;
  margin: 0 10%;
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
@media only screen and (max-width: 600px) {
  .container {
    margin: 0 10%;
  }
}
</style>
