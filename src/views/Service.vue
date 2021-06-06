<template>
    <div>
      <p class="cont">Service</p>
      <Footer/>
    </div>
</template>

<script>
import Footer from '../components/Footer'
export default {
  components: { Footer }
}
</script>

<style scoped>
.cont{
  text-align: center;
  font-size: 80px;
  color: white;
  text-transform: uppercase;
  font-weight: bolder;
  margin: 196px 0;
}
</style>
