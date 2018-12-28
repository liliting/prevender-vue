<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>电话：18888888888</h2>
    <h2>邮箱：ting@li.com</h2>
    <h2>QQ：856856522222222</h2>
    <h2>超链接</h2>
    <ul>
      <li>
        <router-link to="/">首页</router-link>
      </li>
      <li>
        <router-link to="/about">关于我们</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Contact',
  data () {
    return {
      msg: '联系我们'
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
