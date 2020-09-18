<template>
  <div class="footer">
    <h1>{{ msg }}</h1>
    <footer class="page-footer blue lighten-1">
      <div class="container">
        <div class="row center">
          <div class="col l4 s6 center">
            <div class="row">
              <i class="material-icons small">mail</i>
            </div>
            <div class="row">ch.landru@laposte.net</div>
          </div>
          <div class="col l4 s6 center">
            <div class="row">
              <i class="material-icons small">local_phone</i>
            </div>
            <div class="row">+33 6 95 52 95 61</div>
          </div>
          <div class="col l4 s12 center">
            <div class="row">
              <i class="material-icons small">location_on</i>
            </div>
            <div class="row">29 Boulevard Victor Hugo, Nantes</div>
          </div>
        </div>
      </div>
      <div class="footer-copyright">
        <div class="container center">
          <i id="contact_icon" class="material-icons tiny">copyright</i> 2020 Charles Landru - Toute
          réutilisation à but commercial est interdite.
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Footer",
  props: {
    msg: String
  }
};
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
