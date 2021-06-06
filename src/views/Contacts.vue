<template>
    <div>
      <p class="cont">Contacts</p>
      <Footer/>
    </div>
</template>

<script>
import Footer from '../components/Footer'
export default {
  name: 'Contacts',
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
