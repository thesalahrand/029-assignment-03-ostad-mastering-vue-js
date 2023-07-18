<script setup>
const services = [
  {
    flaticonClass: 'flaticon-businessman',
    title: 'Easily Manage',
    shortDesc:
      'Sorem spsum dolor sit amsectetur adipisclit, seddo eiusmod tempor incididunt ut laborea.',
  },
  {
    flaticonClass: 'flaticon-pay',
    title: 'Get Payments Easily',
    shortDesc:
      'Sorem spsum dolor sit amsectetur adipisclit, seddo eiusmod tempor incididunt ut laborea.',
  },
  {
    flaticonClass: 'flaticon-plane',
    title: 'Quick Messaging',
    shortDesc:
      'Sorem spsum dolor sit amsectetur adipisclit, seddo eiusmod tempor incididunt ut laborea.',
  },
]
</script>

<template>
  <section class="service-area sky-blue section-padding2">
    <div class="container">
      <div class="row d-flex justify-content-center">
        <div class="col-lg-6">
          <div class="section-tittle text-center">
            <h2>How Can We HelpYour<br />with Appco!</h2>
          </div>
        </div>
      </div>

      <div class="row">
        <div
          v-for="service in services"
          :key="service.title"
          class="col-xl-4 col-lg-4 col-md-6"
        >
          <div class="services-caption text-center mb-30">
            <div class="service-icon">
              <span :class="service.flaticonClass"></span>
            </div>
            <div class="service-cap">
              <h4>
                <a href="#">{{ service.title }}</a>
              </h4>
              <p>{{ service.shortDesc }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
