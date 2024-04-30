<script>

export default {
  data(){
    return{
      titleText: "La mia prima app con Vite!",
    };
  },

  created(){
    console.log("ciao");
  }
}
</script>

<template>
  <h1>{{ titleText }}</h1>
</template>