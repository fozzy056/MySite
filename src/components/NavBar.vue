<template>
    <header>
        <nav>
            <div class="nav-wrapper blue lighten-1">
                <router-link to="/">Charles Landru</router-link>
                <ul id="nav-mobile" class="right hide-on-med-and-down">
                    <li><router-link to="/">Accueil</router-link></li>
                    <li><router-link to="/pagedetest">Test</router-link></li>
                    <li><router-link to="/about">A propos</router-link></li>
                </ul>
            </div>
        </nav>
    </header>
</template>

<script>
export default {
  name: "NavBar"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
