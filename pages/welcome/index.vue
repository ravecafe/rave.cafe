<template>
  <section class="cafe">
    <div class="gradient-shift"></div>
    <div class="link-container">
      <NuxtLink to="/" class="nav-link">
        <img class="table back" src="~/assets/rave-cafe.png" alt="cafe table" />
        <span class="nav-txt mixes">mixes</span>
      </NuxtLink>
    </div>
    <div class="link-container">
      <NuxtLink to="/" class="nav-link">
        <img class="table" src="~/assets/rave-cafe.png" alt="cafe table" />
        <span class="nav-txt playlists">playlists</span>
      </NuxtLink>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.cafe {
  display: flex;
  justify-content: center;
  margin-top: 20%;
}

.table {
  width: 400px;
  height: auto;
  display: block;
}

.link-container {
  position: relative;
  width: 400px;
}

.nav-txt {
  position: absolute;
  top: 10%;
  left: 50%;
  transform: translateX(-50%);
  font-size: 45px;
  mix-blend-mode: difference;
  opacity: 0;
  transition: opacity 400ms ease;
}

.nav-txt:hover {
  display: block;
}

.nav-txt.mixes {
  margin-top: 20%;
}
.nav-txt.playlists {
  margin-top: 32%;
}

.table:hover + .nav-txt {
  opacity: 1;
  transition: opacity 400ms ease;
}

.table.back {
  width: 280px;
  margin: 0 auto;
}

@media only screen and (max-width: 700px) {
  .cafe {
    flex-direction: column;
  }
  .table + .nav-txt {
    opacity: 1;
    transition: opacity 400ms ease;
  }
}

.gradient-shift {
  position: fixed;
  filter: blur(100px);
  top: 0;
  height: 100%;
  width: 100%;
  background: linear-gradient(356deg, #827e6f, #4f5453, #1a1a1a, #324531);
  background-size: 800% 800%;
  -webkit-animation: cafeShift 54s ease infinite;
  -moz-animation: cafeShift 54s ease infinite;
  -o-animation: cafeShift 54s ease infinite;
  animation: cafeShift 54s ease infinite;
}
@-webkit-keyframes cafeShift {
  0% {
    background-position: 0% 19%;
  }
  50% {
    background-position: 100% 82%;
  }
  100% {
    background-position: 0% 19%;
  }
}
@-moz-keyframes cafeShift {
  0% {
    background-position: 0% 19%;
  }
  50% {
    background-position: 100% 82%;
  }
  100% {
    background-position: 0% 19%;
  }
}
@-o-keyframes cafeShift {
  0% {
    background-position: 0% 19%;
  }
  50% {
    background-position: 100% 82%;
  }
  100% {
    background-position: 0% 19%;
  }
}
@keyframes cafeShift {
  0% {
    background-position: 0% 19%;
  }
  50% {
    background-position: 100% 82%;
  }
  100% {
    background-position: 0% 19%;
  }
}
</style>
