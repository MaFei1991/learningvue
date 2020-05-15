<template>
  <div class="hello">
    <h1>{{ msg }}-欢迎来到{{country}}</h1>
    <p>
     这是一个很长的故事，那我就给大家介绍一下，长话短说，没了。
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',  // 组件名称
  props: {  // 组件属性
    msg: String,
    country: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
