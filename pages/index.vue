<template>
  <div class="container-fluid">
    <div>
      <carousal></carousal>
      <testimonial></testimonial>
      <service></service>
      <contactUs></contactUs>
    </div>
  </div>
</template>

<script>
import carousal from "../components/home/carousal";
import testimonial from "../components/home/testimonial";
import service from "../components/home/service";
import contactUs from "../components/home/contactUs";
export default {
  components:{
    carousal,
    testimonial,
    service,
    contactUs
  },
  comments:{
    carousal
  },
  name: 'IndexPage',
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
