<template>
  <Header @changeTitle="ubahText" :text="text" />
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
      text: "ini adalah text dari data 12345",
    };
  },

  methods:{
    ubahText(newText){
      this.text = newText;
    },
  },
};
</script>

<style>
</style>
