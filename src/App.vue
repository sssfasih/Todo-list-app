<template>
  <div id="app">
    <Header/>
    <router-view/>
    <credits/>
  </div>
</template>

<script>
import Header from "./components/layout/Header";
import credits from "./components/layout/credits";
export default {
  name: 'app',
  components: {
    Header,
    credits
  }
}

</script>



<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
