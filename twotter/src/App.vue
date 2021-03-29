<template>

  <div id="app">
    <UserProfile/>
  </div>
  <!--    @{{ user.username }} - {{ fullName }}-->
  <!--    <strong>Followers:</strong>{{ followers }}-->
  <!--    <button @click="followUser">Follow</button>-->
  <!--  </div>-->

</template>

<script>

import UserProfile from "@/components/UserProfile";

export default {
  name: 'App',
  components: {UserProfile}

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  min-height: 100vh;
  background-color: #F3F5FA;
}
</style>
