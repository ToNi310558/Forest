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
@media only screen and (min-width: 1279px) and (max-width: 1439px){
  .cont{
    font-size: 46px;
    margin: 198px 0;
  }
}
@media screen and (min-width: 1024px) and (max-width: 1279px){
  .cont{
    font-size: 38px;
    margin: 188px 0;
  }
}
</style>
