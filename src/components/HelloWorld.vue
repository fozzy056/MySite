<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Hello</h2>
    <h3>World</h3>
    <h3>Site</h3>
    <h3>en cours</h3>
    <h3>de fabrication</h3>
    <h3>!!!</h3>
  </div>
  
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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
