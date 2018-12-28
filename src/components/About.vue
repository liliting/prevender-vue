<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>合作伙伴</h2>
    <div>
      <img src="../assets/wx.png" alt="">
    </div>
    <h2>底部</h2>
    <ul>
      <li>
        <router-link to="/">首页</router-link>
      </li>
      <li>
        <router-link to="/contact">联系我们</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'About',
  data () {
    return {
      msg: '关于我们'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
