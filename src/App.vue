<template>
  <div id="app">
    <div id="nav">
      <div class="flex">
        <img src="../src/assets/image/logo.png" class="logo" alt="logo">
        <div>
          <label class="container">
            <input type="search" class="search">
            <button class="search-btn"> </button>
          </label>
          <router-link to="/" class="nav-link">Home</router-link>
          <router-link to="/About" class="nav-link">About Us</router-link>
          <router-link to="/Contacts" class="nav-link">Contacts</router-link>
          <router-link to="Service" class="nav-link">Service</router-link>
        </div>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style lang="less">
  //media for 1440px+
#app{
    background: url(../src/assets/image/Forest.jpg) no-repeat center center fixed;
    background-size: cover;
}
.logo{
  width: 133px;
  height: 96px;
  margin-right: 100px;
}
.flex{
  display: flex;
  justify-content: space-around;
  height: 170px;
  align-items: center;
  align-content: center;
  align-self: center;
  text-align: center;
}
.nav-link{
  font-size: 32px;
  font-weight: bolder;
  text-decoration: none;
  color: #fff;
  margin-left: 60px;
}
.nav-link:hover,
.nav-link:active,
.nav-link:focus{
  border-bottom: 5px  solid rgba(255,255,255,0.6);
  border-radius: 5px;
  outline: none;
}
.search{
  border-radius: 10px;
  border: none;
  width: 180px;
  height: 30px;
  position: relative;
  bottom: 5px;
  font-size: 20px;
  padding-left: 6px;
  margin-right: 50px;
  background-color: #fff;
}
.search:focus{
  box-shadow: 0 0 0 2px #aaa inset;
  outline: none;
}
.container{
  position: relative;
}
.search-btn{
  position: absolute;
  background: url("../src/assets/image/Shape.png") no-repeat center #fff;
  background-size: 25px 25px;
  width: 32px;
  height: 30px;
  padding:0 25px;
  right: 19px;
  top: -12px;
  border: none;
  border-radius: 10px;
}
.search-btn:hover{
  background-color: #f4f4f4;
  outline: none;
}
.search-btn:active{
  background-color: #d8d8d8;
  box-shadow: 0 0 0 2px #ababab inset;
  outline: none;
}
//media for 1280-1440px
@media screen and (min-width: 1280px) and (max-width: 1440px) {
  .logo {
    width: 93px;
    height: 67px;
    margin-right: 70px;
  }
  .flex {
    height: 120px;
  }
  .nav-link {
    font-size: 26px;
    margin-left: 42px;
  }
  .nav-link:hover,
  .nav-link:active,
  .nav-link:focus {
    border-bottom: 4px solid rgba(255, 255, 255, 0.6);
    border-radius: 4px;
  }
  .search {
    border-radius: 10px;
    width: 126px;
    height: 24px;
    bottom: 5px;
    font-size: 16px;
    padding-left: 5px;
    margin-right: 35px;
  }
  .search-btn {
    background-size: 18px 18px;
    width: 22px;
    height: 24px;
    padding: 0 18px;
    right: 19px;
    top: -8px;
  }
}
  //media for 1024-1280px
@media screen and (min-width: 1024px) and (max-width: 1279px) {
  .logo{
    width: 80px;
    height: 58px;
    margin-right: 70px;
  }
  .flex{
    height: 170px;
  }
  .nav-link{
    font-size: 24px;
    margin-left: 36px;
  }
  .search{
    width: 120px;
    height: 20px;
    bottom: 3px;
    font-size: 12px;
    padding-left: 4px;
    margin-right: 30px;
  }

  .search-btn{
    background-size: 15px 15px;
    width: 22px;
    height: 20px;
    padding:0 15px;
    right: 15px;
    top: -3px;
  }
}
  //еще не сделал
  //media for 800-1024px
  @media screen and (min-width: 800px) and (max-width: 1023px){
    .logo{
      width: 133px;
      height: 96px;
      margin-right: 100px;
    }
    .flex{
      height: 170px;
    }
    .nav-link{
      font-size: 32px;
      margin-left: 60px;
    }
    .search{
      width: 180px;
      height: 30px;
      bottom: 5px;
      font-size: 20px;
      padding-left: 6px;
      margin-right: 50px;
    }
    .search-btn{
      background-size: 25px 25px;
      width: 32px;
      height: 30px;
      padding:0 25px;
      right: 19px;
      top: -12px;
    }
  }
  //media for 720-799px
  @media screen and (min-width: 720px) and (max-width: 799px){
    .logo{
      width: 133px;
      height: 96px;
      margin-right: 100px;
    }
    .flex{
      height: 170px;
    }
    .nav-link{
      font-size: 32px;
      margin-left: 60px;
    }
    .search{
      width: 180px;
      height: 30px;
      bottom: 5px;
      font-size: 20px;
      padding-left: 6px;
      margin-right: 50px;
    }
    .search-btn{
      background-size: 25px 25px;
      width: 32px;
      height: 30px;
      padding:0 25px;
      right: 19px;
      top: -12px;
    }
  }
  //media for 640-720px
  @media screen and (min-width: 640px) and (max-width: 719px){
    .logo{
      width: 133px;
      height: 96px;
      margin-right: 100px;
    }
    .flex{
      height: 170px;
    }
    .nav-link{
      font-size: 32px;
      margin-left: 60px;
    }
    .search{
      width: 180px;
      height: 30px;
      bottom: 5px;
      font-size: 20px;
      padding-left: 6px;
      margin-right: 50px;
    }
    .search-btn{
      background-size: 25px 25px;
      width: 32px;
      height: 30px;
      padding:0 25px;
      right: 19px;
      top: -12px;
    }
  }
  @media screen and (min-height: 770px){
#app{
  height: 800px;
}
  }
@media screen and (min-height: 800px){
  #app{
    height: 850px;
  }
}
@media screen and (min-height: 850px){
  #app{
    height: 900px;
  }
}
@media screen and (min-height: 900px){
  #app{
    height: 950px;
  }
}
@media screen and (min-height: 950px) {
  #app {
    height: 1000px;
  }
}
@media screen and (min-height: 1000px){
  #app{
    height: 1050px;
  }
}
</style>
