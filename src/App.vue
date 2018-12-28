<template>
  <div id="app">
    <img width="100" src="./assets/logo.png">
    <router-view/>
    <div class="footer">
      <p>Version 1.0.0  © 2018 All Rights Reserved</p>
    </div>
  </div>
  
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
body,html{width:100%;height:100%;position:relative;margin:0;padding:0;}
p{-webkit-margin-before: 0;-webkit-margin-after: 0;}
div{margin:0;padding:0;}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding-top: 60px;
}
.footer{
  width:100%;
  height:50px;
  line-height:50px;
  position: absolute;
  bottom:0;
  left:0;
  background:#f1f1f1;
  /* color: #666; */
}
</style>
