<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <users-list></users-list>
</template> 

<script>
import UsersList from "./components/UsersList.vue";

export default {
  name: "App",

  components: {
    UsersList,
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
  margin-top: 60px;
}
</style>
