<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Je suis étudiant en informatique<p>
    <p>Et en alternance chez BNP Paribas</p>
    <p>Ce site est en cours de fabrication</p>
    <p>En attendant n'hésitez pas a consulter mon profil LinkedIn</p>
    <a class="btn btn-primary blue lighten-1" role="button" href="https://www.linkedin.com/in/charles-landru/" target="_blank">Mon LinkedIn</a>
    <p>Bonne navigation 😉</p>
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
  color: #dde9e4;
}
</style>
