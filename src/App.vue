<template>
  <div id="app">
    <Nav></Nav>
    <router-view />
  </div>
</template>
<script>
import Nav from "@/views/Nav/index.vue";

export default {
  name: 'App',
  components: {
    Nav,
  },
  methods:{
  },

}
</script>
<style lang="less">
*{
  margin: 0;
  padding: 0;

  box-sizing: border-box;
}

a {
  color: inherit;
  text-decoration: none;
}

ul{
  list-style: none;
}

#app {
  width: 100%;
  max-width: 1248px;
  padding: 0 2%;

  margin-left: auto;
  margin-right: auto;

  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
