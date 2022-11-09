<template>
  <!-- tambah ':' - binding didalam props -->
  <Header :text="text" />
  <!-- bawah contoh props sahaja -->
  <!-- <Header :text="data ini adalah dari view" /> -->
</template>

<script>
// import Header from "@/components/Header.vue";
import Header from "./components/Header";

export default {
  name: 'App',
  components:{
    Header,
  },

  data(){
    return{
      text: "ini adalah text dari data 12345"
    }
  }
};
</script>

<style>
</style>
