<script setup>
const testimonials = [
  {
    imgSrc: '/src/assets/img/shape/man3.png',
    title: 'Welcome To The Best Model Winner Contest',
    shortDesc:
      'Utenim ad minim veniam quisnostrud exercitation ullamcolabor nisiut aliquip ex ea commodo consequat duis aute irure dolor in represse.',
  },
  {
    imgSrc: '/src/assets/img/shape/man2.png',
    title: 'Welcome To The Best Model Winner Contest',
    shortDesc:
      'Utenim ad minim veniam quisnostrud exercitation ullamcolabor nisiut aliquip ex ea commodo consequat duis aute irure dolor in represse.',
  },
  {
    imgSrc: '/src/assets/img/shape/man3.png',
    title: 'Welcome To The Best Model Winner Contest',
    shortDesc:
      'Utenim ad minim veniam quisnostrud exercitation ullamcolabor nisiut aliquip ex ea commodo consequat duis aute irure dolor in represse.',
  },
  {
    imgSrc: '/src/assets/img/shape/man2.png',
    title: 'Welcome To The Best Model Winner Contest',
    shortDesc:
      'Utenim ad minim veniam quisnostrud exercitation ullamcolabor nisiut aliquip ex ea commodo consequat duis aute irure dolor in represse.',
  },
]
</script>

<template>
  <div class="our-customer section-padd-top30">
    <div class="container-fluid">
      <div class="our-customer-wrapper">
        <div class="row d-flex justify-content-center">
          <div class="col-xl-8">
            <div class="section-tittle text-center">
              <h2>
                What Our Customers<br />
                Have to Say
              </h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-12">
            <div class="customar-active dot-style d-flex dot-style">
              <div
                class="single-customer mb-100"
                v-for="(testimonial, idx) in testimonials"
                :key="idx"
              >
                <div class="what-img">
                  <img :src="testimonial.imgSrc" alt="" />
                </div>
                <div class="what-cap">
                  <h4>
                    <a href="#">{{ testimonial.title }}</a>
                  </h4>
                  <p>{{ testimonial.shortDesc }}</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
