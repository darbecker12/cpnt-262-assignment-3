<script setup>
  defineProps({
    title: {
      type: String,
      default: "This is my Header",
    },
    description: {
      type: String,
      default: "This is the description of my header",
    },
  });
</script>
<template>
  <header>
    <h1 class="title">{{title}}</h1>
    <p class="description">{{description}}</p>

  </header>

</template>


<style> 
  .title{
    text-align: center;
    color: black;
    font-size:50px;
    background: lightskyblue;
  }
  .description{
    text-align: center;
    color: black;
    font-size: 30px;
    background: lightskyblue;
  }
</style>