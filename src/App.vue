<template>
  <div id="app">
    <div id="nav">
      <div class="flex">
        <img src="../src/assets/image/logo.png" style="width: 133px; height: 96px; margin-right: 100px;" >
        <div>
          <label class="container">
            <input type="search" class="search">
            <button class="search-btn"> </button>
          </label>
          <router-link to="/" class="nav-link">Home</router-link>
          <router-link to="/About" class="nav-link">About US</router-link>
          <router-link to="/Contacts" class="nav-link">Contacts</router-link>
          <router-link to="Service" class="nav-link">Service</router-link>
        </div>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style lang="less">
#app{
    background: url(../src/assets/image/Forest.jpg) no-repeat center;
    background-size: cover;
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
</style>
