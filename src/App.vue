<template>
 <!--<img alt="Vue logo" src="./assets/logo.png">--> 
 <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
  <div class="nav-bar">
    <van-nav-bar>
      <div class="title">个人基本信息</div>
    </van-nav-bar>
  </div>

  <div class="personal-page">
    <img :src="one" alt="One">
    <h2>{{ sname }}</h2>
    <p>{{ id }}</p>
  </div>   
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  data(){
    return{
      one:"../Images/one.jpg",
      sname:"chenyu",
      id:"2310273036"
    };
  }
 // name: 'App',
 // components: {
 //   HelloWorld
//  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
