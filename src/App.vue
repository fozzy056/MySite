<template>
  <div id="app">
      <carousel-3d>
    <slide :index="0">
      <img alt="Vue logod" src="https://cloud.leparking.fr/2019/09/25/00/19/seat-ibiza-ibiza-6l-fr-1-8t-20vt-150cv_7119317655.jpg" />
    </slide>
    <slide :index="1">
      <img alt="Vue logoz" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTF4V8PdD80GGg0_vFh8xIWsrGqHEFJ8MqsGZSAnpkAtIf-1JY&s" />
    </slide>
    <slide :index="2">
      <img alt="Vue logo" src="https://bnperfshop.com/wp-content/uploads/2019/09/SEAT-IBIZA-00.jpg" />
    </slide>
    <slide :index="3">
      <img alt="Vue logog" src="https://i.ebayimg.com/images/g/a~4AAOSwljFeUA1W/s-l400.jpg" />
    </slide>
    <slide :index="4">
      <img alt="Vue logog" src="https://cloud.leparking.fr/2019/08/24/12/44/seat-ibiza-seat-ibiza-6l-1-4l-dab-special-jaune_7041994038.jpg" />
    </slide>
  </carousel-3d>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Est ce que c'est bô ?" />
    <footer class="page-footer blue lighten-1">
        <div class="container">
            <div class="row center">
                <div class="col l4 s6 center">
                    <div class="row">
                        <i class="material-icons small">mail</i>
                    </div>
                    <div class="row">
                        ch.landru@laposte.net
                    </div>
                </div>
                <div class="col l4 s6 center">
                    <div class="row">
                        <i class="material-icons small">local_phone</i>
                    </div>
                    <div class="row">+33 6 95 52 95 61
                    </div>
                </div>
                <div class="col l4 s12 center">
                    <div class="row">
                        <i class="material-icons small">location_on</i>
                    </div>
                    <div class="row">25 Trévelo 56130 Péaule France
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-copyright">
            <div class="container center">
                <i id="contact_icon" class="material-icons tiny">copyright</i> 2019 Charles Landru - Toute
                réutilisation à but commercial est interdite.
                <a class="grey-text text-lighten-4 right" href="#!"></a>
            </div>
        </div>
    </footer>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
