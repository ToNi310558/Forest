<template>
  <div>
    <main class="main-home">
      <div>
        <p class="title">World <span class="bold">Forest Day</span></p>
      </div>
      <div class="main">
        <p class="lorem">Lorem ipsum dolor sit amet, consectetur adipisicing elit
          sed to eiusmod tempor incididunt ut labore et dolore.</p>
        <h1 class="heading">Preserve the Forest, Protect the Future</h1>
        <router-link to="/About">
          <button class="learnmore">Learn More</button>
        </router-link>

      </div>
    </main>
    <Footer/>
  </div>
</template>

<script>

import Footer from '../components/Footer'
export default {
  name: 'Home',
  components: {
    Footer
  }
}
</script>

<style lang="less">
  @shadow: 1px 0 1px #000,
  0 1px 1px #000,
  -1px 0 1px #000,
    0 -1px 1px #000;
  .main-home{
    color: white;
    display: flex;
    justify-content: space-around;
  }
  .main{
    text-align: center;
    width: 800px;
    padding-right: 90px;
  }
  .title{
    margin: 0;
    color: #303336;
    font-size: 68px;
    transform: rotate(-90deg);
    position: relative;
    top: 188px;
    right: 178px;
  }
  .bold{
    font-weight: bolder;
  }
  .heading{
    font-size: 88px;
    font-weight: bolder;
    margin: 0;
  }
  .lorem{
    font-size: 28px;
    width: 640px;
    margin: 30px auto 2px auto;
  }
  .learnmore{
    margin: 50px 0 100px 0 ;
    width: 200px;
    height: 36px;
    border-radius: 20px;
    border: none;
    font-size: 16px;
    background-color: white;
    font-weight: bolder;
    color: #303336;
  }
  .learnmore:hover{
    background-color: #f4f4f4;
    outline: none;
  }
  .learnmore:active{
    background-color: #d8d8d8;
    box-shadow: 0 0 0 2px #ababab inset;
    outline: none;
  }
  @media all and (min-width: 1279px) and (max-width: 1439px) {
    .main{
      width: 560px;
      padding-right: 64px;
    }
    .title{
      font-size: 56px;
      top: 160px;
      right: 150px;
    }
    .heading{
      font-size: 62px;
    }
    .lorem{
      font-size: 22px;
      width: 520px;
      margin: 40px auto 40px auto;
    }
    .learnmore{
      margin: 50px 0 100px 0 ;
      width: 140px;
      height: 26px;
      font-size: 12px;
    }
  }

  @media all and (min-width: 1024px) and (max-width: 1279px){
    .main{
      width: 500px;
      padding-right: 54px;
    }
    .title{
      font-size: 52px;
      top: 140px;
      right: 140px;
    }
    .heading{
      font-size: 54px;
    }
    .lorem{
      font-size: 20px;
      width: 460px;
      margin: 30px auto 30px auto;
    }
    .learnmore{
      margin: 50px 0 120px 0 ;
      width: 120px;
      height: 22px;
      font-size: 10px;
    }
  }
  @media all and (min-width: 800px) and (max-width: 1023px){
    .main{
      width: 430px;
      padding-right: 45px;
    }
    .title{
      font-size: 44px;
      top: 120px;
      right: 115px;
    }
    .heading{
      font-size: 50px;
    }
    .lorem{
      font-size: 18px;
      width: 420px;
      margin: 15px auto 50px auto;
    }
    .learnmore{
      margin: 50px 0 110px 0 ;
      width: 140px;
      height: 24px;
      font-size: 14px;
    }
  }
  @media all and (min-width: 640px) and (max-width: 799px){
    .main{
      width: 360px;
      padding-right: 20px;
    }
    .title{
      font-size: 34px;
      top: 120px;
      right: 100px;
    }
    .heading{
      font-size: 40px;
    }
    .lorem{
      font-size: 15px;
      width: 340px;
      margin: 14px auto 40px auto;
    }
    .learnmore{
      margin: 50px 0 110px 0 ;
      width: 100px;
      height: 22px;
      font-size: 11px;
    }
  }
  @media all and (max-width: 640px){
    .main-home{
    display: block;
      text-align: center;
    }
    .main{
      text-align: center;
      width: auto;
      padding-right: 0;
      margin: 0;
    }
    .title{
      display: none;
    }
    .heading{
      font-size: 36px;
      margin: 0 auto;
      text-shadow: @shadow;
      width: 340px;
    }
    .lorem{
      font-size: 16px;
      width: 300px;
      margin: 50px auto 10px auto;
      text-shadow: @shadow;
    }
    .learnmore{
      margin: 30px 0 60px 0 ;
      width: 140px;
      height: 32px;
      font-size: 15px;
    }
  }
</style>
