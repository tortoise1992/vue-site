<template>
  <div>
      <v-nav></v-nav>
      <router-view></router-view>
  </div>
</template>

<script>
    import nav from 'components/nav/nav'
    export default {
        components:{
            'v-nav':nav
        }
    }
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
