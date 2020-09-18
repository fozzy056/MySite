<template>
  <div id="test">
      <h1>Page de test</h1>
            <carousel-3d>
    <slide :index="0">
      <img alt="Ibiza 1" src="https://cloud.leparking.fr/2019/09/25/00/19/seat-ibiza-ibiza-6l-fr-1-8t-20vt-150cv_7119317655.jpg" />
    </slide>
    <slide :index="1">
      <img alt="Ibiza 2" src="https://aws-cf.caradisiac.com/prod/mesimages/225467/Ma%20voiture5.JPG" />
    </slide>
    <slide :index="2">
      <img alt="Ibiza 3" src="https://bnperfshop.com/wp-content/uploads/2019/09/SEAT-IBIZA-00.jpg" />
    </slide>
    <slide :index="3">
      <img alt="Ibiza 4" src="https://i.ebayimg.com/images/g/a~4AAOSwljFeUA1W/s-l400.jpg" />
    </slide>
    <slide :index="4">
      <img alt="Ibiza 5" src="https://images.caradisiac.com/photo/0/1/6/4/20164/S0-IBIZA-CUPRA-FILE-photo16512-20164.jpg" />
    </slide>
  </carousel-3d>

  <img alt="Vue logo" src="@/assets/logo.png" />

  <h3>Tests</h3>
  <a class="waves-effect waves-light btn">button</a>
  <a class="waves-effect waves-light btn"><i class="material-icons left">cloud</i>button</a>
  <p>
    <label>
      <input type="checkbox" />
      <span>Cochez moi !</span>
    </label>
  </p>
  <h3>Ecosystem</h3>
  <ul>
    <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
    <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
    <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
    <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
    <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
  </ul>    
  </div>
</template>

<script>
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
