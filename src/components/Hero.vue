<script setup></script>

<template>
  <div class="slider-area">
    <div class="slider-active">
      <div
        class="single-slider slider-height slider-padding sky-blue d-flex align-items-center"
      >
        <div class="container">
          <div class="row d-flex align-items-center">
            <div class="col-lg-6 col-md-9">
              <div class="hero__caption">
                <span data-animation="fadeInUp" data-delay=".4s"
                  >App Landing Page</span
                >
                <h1 data-animation="fadeInUp" data-delay=".6s">
                  Get things done<br />with Appco
                </h1>
                <p data-animation="fadeInUp" data-delay=".8s">
                  Dorem ipsum dolor sitamet, consectetur adipiscing elit, sed do
                  eiusm tempor incididunt ulabore et dolore magna aliqua.
                </p>

                <div class="slider-btns">
                  <a
                    data-animation="fadeInLeft"
                    data-delay="1.0s"
                    href="industries.html"
                    class="btn radius-btn"
                    >Download</a
                  >

                  <a
                    data-animation="fadeInRight"
                    data-delay="1.0s"
                    class="popup-video video-btn ani-btn"
                    href="https://www.youtube.com/watch?v=1aP-TXUpNoU"
                    ><i class="fas fa-play"></i
                  ></a>
                </div>
              </div>
            </div>
            <div class="col-lg-6">
              <div
                class="hero__img d-none d-lg-block f-right"
                data-animation="fadeInRight"
                data-delay="1s"
              >
                <img src="/src/assets/img/hero/hero_right.png" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
