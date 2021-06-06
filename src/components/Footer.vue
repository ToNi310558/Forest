<template>
  <div class="footer">
    <div class="info">
      <h3><span>21</span> March</h3>
      <p>Av.Lorem ipsum dolor 2045</p>
      <p>Dolor sit Amet - Adress</p>
    </div>
    <div class="hrefs">
      <router-link to="/" class="yoursite">yoursite</router-link>
      <router-link to="/"><img src="../assets/image/facebook.png">your account</router-link>
      <router-link to="/"><img src="../assets/image/insta.png">your account</router-link>
      <router-link to="/"><img src="../assets/image/twitter.png">your account</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>
  .footer{
    display: flex;
    justify-content: space-around;
  }
  .yoursite{
    color: white;
    font-size: 24px;
    text-transform: uppercase;
    text-decoration: none;
    font-weight: bolder;
    margin-right: 14px;
  }
  a{
    margin-left: 60px;
    padding: 0 14px;
    text-decoration: none;
    color: white;
    font-size: 20px;
  }
  a:hover{
    color: #d8d8d8;
    border-bottom: 1px solid #ababab;
  }
  img{
    width: 24px;
    height: 24px;
    padding-right: 20px;
    position: relative;
    top: 6px;
  }
  .hrefs{
    padding-top: 60px;
    padding-bottom: 10px;
    height: 40px;
  }
  h3{
    margin: 0;
    padding: 0;
    font-weight: bolder;
    font-size: 26px;
  }
  span{
    font-size: 34px;
  }
  p{
    font-size:16px;
    color: #303336;
    font-weight: bolder;
    line-height: 8px;
  }
  .info{
    padding-right: 80px;
  }
</style>
