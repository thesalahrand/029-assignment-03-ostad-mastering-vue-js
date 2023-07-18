<script setup>
const screenshots = [
  '/src/assets/img/gallery/App1.png',
  '/src/assets/img/gallery/App2.png',
  '/src/assets/img/gallery/App3.png',
  '/src/assets/img/gallery/App2.png',
  '/src/assets/img/gallery/App1.png',
]
</script>

<template>
  <div class="applic-apps section-padding2">
    <div class="container-fluid">
      <div class="row">
        <div class="col-xl-4 col-lg-4 col-md-8">
          <div class="single-cases-info mb-30">
            <h3>
              Applic Apps<br />
              Screenshot
            </h3>
            <p>
              Lorem ipsum dolor sit amet, consecadipiscing elit, sed do eiusmod
              tempor incididunt ut ore et dolore magna aliqua. Quis ipsum
              suspendisse gravida. Risus commodo viverra maecenasan lacus vel
              facilisis.
            </p>
          </div>
        </div>

        <div class="col-xl-8 col-lg-8 col-md-col-md-7">
          <div class="app-active owl-carousel">
            <div
              class="single-cases-img"
              v-for="(screenshot, idx) in screenshots"
              :key="idx"
            >
              <img :src="screenshot" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
