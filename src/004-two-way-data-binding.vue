<template>
  <input type="text" v-model="nama">
  {{ nama }}
<!-- div.myclass#myid -->
<!-- div>span -->
<!-- ul>li*3 -->
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
       nama: "syarul azwan"
    };
  },
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
