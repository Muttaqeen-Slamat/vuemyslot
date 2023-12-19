<template>
  <Button @click="helloText" >
    <slot name="text">Hello</slot>
  </Button>
  <Button>
    <slot>Click <img src="https://picsum.photos/seed/picsum/200/300" alt="logo"></slot>
  </Button>
</template>

<script>

import Button from './components/Button.vue';

export default {
  name: 'App',
  components: {
    Button
    
  }
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
img{
  width: 2rem;
  aspect-ratio: 1/1;

}
button{
  background-color: chartreuse;
  border-radius: 12px;
  padding: 10px;
  color: crimson;
  font-size: larger;
}

:hover button{
  background-color: crimson;
  border-radius: 12px;
  padding: 10px;
  color: chartreuse;
  font-size: larger;
}
</style>
