<template>
  <section class="container">
    <h1>we miss you</h1>
    <p>
      we wanted to put together a snapshot of our year and share it with all of
      you
    </p>
    <section class="month-cell">
      <h2>January</h2>
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
      <h2>February</h2>
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
      <h2>March</h2>
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
  justify-content: center;
  align-items: center;
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
@media only screen and (max-width: 600px) {
  .container {
    margin: 0 10%;
  }
}
</style>
