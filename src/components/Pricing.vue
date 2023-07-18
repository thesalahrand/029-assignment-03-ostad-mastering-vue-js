<script setup>
const packages = [
  {
    duration: '1 Year',
    monthlyCost: '20',
    benefits: [
      'Increase traffic 50%',
      'E-mail support',
      '10 Free Optimization',
      '24/7 support',
    ],
  },
  {
    duration: '2 Years',
    monthlyCost: '10',
    benefits: [
      'Increase traffic 50%',
      'E-mail support',
      '10 Free Optimization',
      '24/7 support',
    ],
  },
  {
    duration: '5 Years',
    monthlyCost: '7',
    benefits: [
      'Increase traffic 50%',
      'E-mail support',
      '10 Free Optimization',
      '24/7 support',
    ],
  },
]
</script>

<template>
  <div>
    <section
      class="best-pricing pricing-padding"
      data-background="src/assets/img/gallery/best_pricingbg.jpg"
    >
      <div class="container">
        <div class="row d-flex justify-content-center">
          <div class="col-lg-6 col-md-8">
            <div class="section-tittle section-tittle2 text-center">
              <h2>Choose Your Very Best Pricing Plan.</h2>
            </div>
          </div>
        </div>
      </div>
    </section>

    <div class="pricing-card-area">
      <div class="container">
        <div class="row">
          <div
            class="col-xl-4 col-lg-4 col-md-6"
            v-for="(_package, idx) in packages"
            :key="idx"
          >
            <div class="single-card text-center mb-30">
              <div class="card-top">
                <span>{{ _package.duration }}</span>
                <h4>${{ _package.monthlyCost }} <span>/ month</span></h4>
              </div>
              <div class="card-bottom">
                <ul>
                  <li
                    v-for="(benefit, idx) in _package.benefits"
                    :key="idx + benefit"
                  >
                    {{ benefit }}
                  </li>
                </ul>
                <a href="#" class="btn card-btn1">Get Started</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
