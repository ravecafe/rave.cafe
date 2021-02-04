<template>
  <section class="garden">
    <h1 class="mu-title">garden</h1>
    <p>
      Welcome to our indoor garden. <br />
      Our plants enjoy infrared light & words of affirmation. <br />Seat
      yourself anywhere you'd like.
    </p>
    <div class="plant">
      <a
        href="https://www.notion.so/seeing-0d1ed9d120534498bc8b0f51438f9e5e"
        target="_blank"
        rel="nooopener"
      >
        <span>seeing</span>
        <img src="~/assets/garden/DSCF1414.jpg" alt="plant" />
      </a>
    </div>
    <div class="plant">
      <a
        href="https://www.notion.so/hearing-ee967f59022945ddb02274302f455973"
        target="_blank"
        rel="nooopener"
      >
        <span>hearing</span>
        <img src="~/assets/garden/DSCF1404.jpg" alt="plant" />
      </a>
    </div>
    <div class="plant">
      <a
        href="https://www.notion.so/smelling-befcd7bd20c646f5b24e0db2410f83df"
        target="_blank"
        rel="nooopener"
      >
        <span>smelling</span>
        <img src="~/assets/garden/DSCF1397.jpg" alt="plant" />
      </a>
    </div>
    <div class="plant">
      <a
        href="https://www.notion.so/tasting-6ff593e0039645b288226215f22ba4fb"
        target="_blank"
        rel="nooopener"
      >
        <span>tasting</span>
        <img class="floor" src="~/assets/garden/DSCF1388.jpg" alt="plant" />
      </a>
    </div>
    <div class="plant">
      <a
        href="https://www.notion.so/feeling-61c7217ffb8249c2a801474679ee7854"
        target="_blank"
        rel="nooopener"
      >
        <span>feeling</span>
        <img src="~/assets/garden/DSCF1387.jpg" alt="plant" />
      </a>
    </div>

    <div class="table-wrapper">
      <NuxtLink to="/welcome">
        <img class="table" src="~/assets/garden/table.png" alt="plant" />
      </NuxtLink>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.garden {
  width: 100%;
  overflow: hidden;
}
.mu-title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: normal;
  font-size: 80px;
  color: #fff;
  width: 80%;
  border-bottom: 1px solid #fff;
  letter-spacing: 1px;
  mix-blend-mode: difference;
  padding: 20px;
  margin-left: 10%;
  margin-bottom: 20px;
  text-align: center;
}

p {
  text-align: center;
}

.garden img {
  width: 100%;
}
.plant {
  position: relative;
  width: 80%;
  left: 10%;
  margin: 5% 0;
}
.plant span {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 5rem;
  z-index: -1;
}
.plant img:hover {
  mix-blend-mode: multiply;
}
.table-wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
}
a {
  display: block;
}
img.table {
  width: 200px;
  left: 0;
}
img.table:hover {
  animation: rotation 5s infinite linear;
}
@keyframes rotation {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(359deg);
  }
}

@media only screen and (max-width: 600px) {
  .plant span {
    font-size: 3rem;
  }
  a:hover img {
    mix-blend-mode: none;
  }
}
</style>
