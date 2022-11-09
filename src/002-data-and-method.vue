<template>
<h2>Name: {{ nama }}</h2>
<button @click="changeName">CHANGE NAME</button>
<!-- div.myclass#myid -->
<!-- div>span -->
<!-- ul>li*3 -->
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
        nama: "SYARUL AZWAN",
    };
    
  },
  

  methods: {
    changeName(){
        this.nama = "tari kemas";
    },
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
