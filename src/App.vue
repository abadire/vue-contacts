<template>
  {{ user.username }}
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      user: {
        username: 'van',
      },
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: violet;
  width: 100%;
  height: 100vh;
}
</style>
