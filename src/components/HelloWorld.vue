<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>忽然之间-莫文蔚</h2>
    <ul>
      <li>忽然之间</li>
      <li>天昏地暗</li>
      <li>世界可以忽然什么都没有</li>
      <li>我想起了你</li>
      <li>再想到自己</li>
    </ul>
    <h2>歌曲</h2>
    <ul>
      <li><router-link to="/about">慢慢喜欢你</router-link></li>
      <li><router-link to="/contact">因为慢慢是个最好的原因</router-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '我是预渲染页面没有动态获取数据'
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
