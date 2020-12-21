<template>
  <section class="container">
    <h1 class="title-right">we miss you</h1>
    <div class="logo-wrap">
      <Logo height="50" />
    </div>
    <section class="month-cell">
      <h2>01 - january</h2>
      <img src="~/assets/miss-u/01/000065770010.jpg" />
      <img src="~/assets/miss-u/01/DSCF0446.JPG" />
      <img src="~/assets/miss-u/01/DSCF0471.JPG" />
    </section>
    <section class="month-cell">
      <h2>02 - february</h2>
      <img src="~/assets/miss-u/02/DSCF0510.JPG" />
    </section>
    <section class="month-cell">
      <h2>03 - march</h2>
      <img src="~/assets/miss-u/03/000326160013.jpg" />
      <img src="~/assets/miss-u/03/000326160030.jpg" />
      <img src="~/assets/miss-u/03/DSCF0659.JPG" />
    </section>
    <section class="month-cell">
      <h2>04 - april</h2>
      <img src="~/assets/miss-u/04/DSCF0514.JPG" />
    </section>
    <section class="month-cell">
      <h2>05 - may</h2>
      <img src="~/assets/miss-u/05/DSCF0638.JPG" />
      <img src="~/assets/miss-u/05/DSCF0782.JPG" />
    </section>
    <section class="month-cell">
      <h2>06 - june</h2>
      <img src="~/assets/miss-u/06/000125600032.jpg" />
      <img src="~/assets/miss-u/06/DSCF0802.JPG" />
    </section>
    <section class="month-cell">
      <h2>07 - july</h2>
      <img src="~/assets/miss-u/07/DSCF0890.JPG" />
      <img src="~/assets/miss-u/07/000125560023.jpg" />
      <img src="~/assets/miss-u/07/000326160031.jpg" />
    </section>
    <section class="month-cell">
      <h2>08 - august</h2>
      <img src="~/assets/miss-u/08/000125550014.jpg" />
      <img src="~/assets/miss-u/08/000125570026.jpg" />
    </section>
    <section class="month-cell">
      <h2>09 - september</h2>
      <img src="~/assets/miss-u/09/000125570014 (1).jpg" />
      <img src="~/assets/miss-u/09/000125600004.jpg" />
    </section>
    <section class="month-cell">
      <h2>10 - october</h2>
      <img src="~/assets/miss-u/10/000133070027.jpg" />
      <img src="~/assets/miss-u/10/000133070029.jpg" />
    </section>
    <section class="month-cell">
      <h2>11 - november</h2>
      <img src="~/assets/miss-u/11/000326100020.jpg" />
    </section>
    <section class="month-cell">
      <h2>12 - december</h2>
      <img src="~/assets/miss-u/12/DSCF1282.JPG" />
    </section>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.title-right {
  text-align: right;
}
.logo-wrap {
  margin: 5% auto 0;
}
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
