<template>
  <div id="app">
    <HeaderComponent />
    <router-view/>
  </div>
</template>

<script>
import HeaderComponent from "../src/components/HeaderComponent.vue"
import BootstrapVue from "bootstrap-vue";
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components:{
    HeaderComponent,
    BootstrapVue
  }
}
</script>


<style lang="scss">
@import "~bootstrap/scss/bootstrap.scss";

p, div{
  font-size: 1.2rem;
}

.text-marked{
  color:#1CB5E0;
}

.box{
  min-height: 40rem;
}

section{
  background-color:#eeeeee;
  padding: 5rem 0;
}


section:nth-child(even){
    background-color: white;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align:justify;
  color: #2c3e50;

  h1{
    text-align: center;
  }
}
nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>