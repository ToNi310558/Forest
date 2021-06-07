<template>
  <div class="footer">
    <div class="info">
      <h3><span>21</span> March</h3>
      <p>Av.Lorem ipsum dolor 2045</p>
      <p>Dolor sit Amet - Adress</p>
    </div>
    <div class="hrefs">
      <router-link to="/" class="yoursite">yoursite</router-link>
      <router-link to="/"><img src="../assets/image/facebook.png" alt="facebook">your account</router-link>
      <router-link to="/"><img src="../assets/image/insta.png" alt="instagram">your account</router-link>
      <router-link to="/"><img src="../assets/image/twitter.png" alt="twitter">your account</router-link>
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
    width: 20px;
    height: 20px;
    padding-right: 20px;
    position: relative;
    top: 4px;
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
    font-size: 30px;
  }
  p{
    font-size:16px;
    color: black;
    font-weight: bolder;
    line-height: 8px;
  }
  .info{
    padding-right: 80px;
  }
  @media only screen and (min-width: 1279px) and (max-width: 1439px){
    .footer{
      padding-top: 20px;
    }
    .yoursite{
      font-size: 20px;
      margin-right: 10px;
    }
    a{
      margin-left: 30px;
      padding: 0 10px;
      font-size: 16px;
    }
    img{
      width: 16px;
      height: 16px;
      padding-right: 16px;
      top: 3px;
    }
    .hrefs{
      padding-top: 52px;
      padding-bottom: 40px;
      height: 40px;
    }
    h3{
      font-size: 21px;
    }
    span{
      font-size: 24px;
    }
    p{
      font-size: 14px;
      line-height: 7px;
    }
    .info{
      padding-right: 40px;
    }
  }
  @media screen and (min-width: 1024px) and (max-width: 1279px){
    .yoursite{
      font-size: 14px;
      margin-right: 8px;
    }
    a{
      margin-left: 36px;
      padding: 0 8px;
      font-size: 16px;
    }
    img{
      width: 12px;
      height: 12px;
      padding-right: 16px;
      top: 4px;
    }
    .hrefs{
      padding-top: 40px;
      padding-bottom: 52px;
      height: 40px;
    }
    h3{
      font-size: 18px;
    }
    span{
      font-size: 18px;
    }
    p{
      font-size:14px;
      line-height: 6px;
    }
    .info{
      padding-right: 2px;
    }
  }
  @media screen and (min-width: 800px) and (max-width: 1023px){
    .yoursite{
      font-size: 15px;
      margin-right: 5px;
    }
    a{
      margin-left: 20px;
      padding: 0 7px;
      font-size: 12px;
    }
    img{
      width: 10px;
      height: 10px;
      top: 2px;
    }
    .hrefs{
      padding-top: 40px;
      padding-bottom: 10px;
      height: 20px;
    }
    h3{
      font-size: 16px;
    }
    span{
      font-size: 18px;
    }
    p{
      font-size:12px;
      line-height: 6px;
    }
    .info{
      padding-right: 20px;
    }
  }
  @media screen and (min-width: 640px) and (max-width: 799px){
    .yoursite{
      font-size: 12px;
      margin-right: 4px;
    }
    a{
      margin-left: 12px;
      padding: 0 6px;
      font-size: 11px;
    }
    img{
      width: 9px;
      height: 9px;
      top: 2px;
    }
    .hrefs{
      padding-top: 34px;
      padding-bottom: 10px;
      height: 18px;
    }
    h3{
      font-size: 12px;
    }
    span{
      font-size: 14px;
    }
    p{
      font-size: 10px;
      line-height: 5px;
    }
    .info{
      padding-right: 10px;
    }
  }
</style>
