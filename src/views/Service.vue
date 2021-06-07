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
@media all and (min-width: 1279px) and (max-width: 1439px){
  .cont{
    font-size: 46px;
    margin: 198px 0;
  }
}
@media all and (min-width: 1024px) and (max-width: 1279px){
  .cont{
    font-size: 38px;
    margin: 188px 0;
  }
} @media all and (min-width: 800px) and (max-width: 1023px){
  .cont{
    font-size: 34px;
    margin: 186px 0;
  }
}
@media all and (min-width: 640px) and (max-width: 799px){
  .cont{
    font-size: 30px;
    margin: 160px 0;
  }
}
@media all and (max-width: 640px){
  .cont{
    font-size: 30px;
    margin: 150px 0;
    text-shadow:  1px 0 1px #000,
    0 1px 1px #000,
    -1px 0 1px #000,
    0 -1px 1px #000;
  }
}

</style>
