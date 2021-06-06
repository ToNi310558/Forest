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

<style>
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
</style>
