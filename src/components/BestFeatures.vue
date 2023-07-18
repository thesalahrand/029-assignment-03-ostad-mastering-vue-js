<script setup>
const features = [
  {
    flaticonClass: 'flaticon-support',
    title: 'Easy to Customize',
    shortDesc: 'Aorem psum olorsit amet ectetur adipiscing elit, sed dov.',
  },
  {
    flaticonClass: 'flaticon-support',
    title: 'Extreme Security',
    shortDesc: 'Aorem psum olorsit amet ectetur adipiscing elit, sed dov.',
  },
  {
    flaticonClass: 'flaticon-support',
    title: 'Customer Support',
    shortDesc: 'Aorem psum olorsit amet ectetur adipiscing elit, sed dov.',
  },
  {
    flaticonClass: 'flaticon-support',
    title: 'Creative Design',
    shortDesc: 'Aorem psum olorsit amet ectetur adipiscing elit, sed dov.',
  },
]
</script>

<template>
  <section class="best-features-area section-padd4">
    <div class="container">
      <div class="row justify-content-end">
        <div class="col-xl-8 col-lg-10">
          <div class="row">
            <div class="col-lg-10 col-md-10">
              <div class="section-tittle">
                <h2>Some of the best features Of Our App!</h2>
              </div>
            </div>
          </div>

          <div class="row">
            <div
              v-for="feature in features"
              :key="feature.title"
              class="col-xl-6 col-lg-6 col-md-6"
            >
              <div class="single-features mb-70">
                <div class="features-icon">
                  <span :class="feature.flaticonClass"></span>
                </div>
                <div class="features-caption">
                  <h3>{{ feature.title }}</h3>
                  <p>{{ feature.shortDesc }}</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="features-shpae d-none d-lg-block">
      <img src="/src/assets/img/shape/best-features.png" alt="" />
    </div>
  </section>
</template>

<style scoped></style>
