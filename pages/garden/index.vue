<template>
  <section class="garden">
    <a
      href="https://www.notion.so/feeling-61c7217ffb8249c2a801474679ee7854"
      target="_blank"
      rel="nooopener"
    >
      <img class="snake" src="~/assets/garden/sanseveria.png" />
    </a>
    <a
      href="https://www.notion.so/tasting-6ff593e0039645b288226215f22ba4fb"
      target="_blank"
      rel="nooopener"
    >
      <img
        class="jelly"
        src="~/assets/garden/jellyfish.png"
        target="_blank"
        rel="nooopener"
      />
    </a>
    <a
      href="https://www.notion.so/smelling-befcd7bd20c646f5b24e0db2410f83df"
      target="_blank"
      rel="nooopener"
    >
      <img class="floor" src="~/assets/garden/IMG_3021.png" />
    </a>
    <a
      href="https://www.notion.so/seeing-0d1ed9d120534498bc8b0f51438f9e5e"
      target="_blank"
      rel="nooopener"
    >
      <img class="flowers" src="~/assets/garden/flowers.png" />
    </a>
    <a
      href="https://www.notion.so/hearing-ee967f59022945ddb02274302f455973"
      target="_blank"
      rel="nooopener"
    >
      <img class="flowy" src="~/assets/garden/flowy.png" />
    </a>

    <img class="table" src="~/assets/garden/table.png" />
  </section>
</template>

<script>
export default {}
</script>

<style>
.garden {
  position: relative;
  width: 100%;
  height: 100vh;
  overflow: hidden;
}
.snake {
  width: 300px;
  position: absolute;
  bottom: 0;
  left: 0;
  opacity: 0.7;
}
.jelly {
  width: 300px;
  position: absolute;
  right: 10px;
  top: 10px;
  transform: rotate(30deg);
  opacity: 0.8;
}
.floor {
  position: absolute;
  width: 350px;
  bottom: 0;
  right: 0;
  opacity: 0.6;
}
.flowers {
  width: 200px;
  opacity: 0.7;
  position: absolute;
  margin: 0 auto;
  left: 0;
  right: 10px;
  top: 30vh;
}
.flowy {
  opacity: 0.7;
  position: absolute;
  width: 400px;
  margin: 0 auto;
  left: 0;
  top: 0;
  transform: rotate(90deg);
}
.table {
  opacity: 0.9;
  position: absolute;
  width: 50vw;
  margin: 0 auto;
  left: 0;
  right: 0;
  top: 40vh;
}
@media only screen and (max-width: 600px) {
  .garden {
    position: relative;
    width: 100%;
    height: 500vh;
    overflow: hidden;
  }
  .table {
    width: 90vw;
  }
}
</style>
