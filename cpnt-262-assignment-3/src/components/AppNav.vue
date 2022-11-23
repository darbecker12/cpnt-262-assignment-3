<script>
  export default {
    data() {
      return {
        textStyle: {
          color: 'red',
          fontSize: '20px',
        }
      }
    }
  }
</script>

<template>
   <nav>
        <h1 v-bind:style="textStyle">CPNT262 Assignment 3</h1>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
</template>

<style>
  nav{
    display: flex;
    justify-content: space-evenly;
    border: 1px solid grey;
    background: black;
  }
</style>