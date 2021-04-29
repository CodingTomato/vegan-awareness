<template>
  <div class="bg-gray-50 dark:bg-gray-700 text-gray-900 dark:text-gray-50">
    <div id="nav" class="flex bg-gray-300 dark:bg-gray-900 p-5 shadow">
      <div id="title" class="flex-1 font-semibold">
        <h1 class="subpixel-antialiased text-xl">YOUR CHOICE</h1>
      </div>
      <div id="links" class="flex-2 ml-2 inline-block align-middle">
        <a href="#">TEST1</a>
      </div>
      <div id="links" class="flex-3 ml-2 inline-block align-middle">
        <a href="#">TEST2</a>
      </div>
      <div id="links" class="flex-4 ml-2 inline-block align-middle">
        <a href="#">TEST3</a>
      </div>
    </div>
    <router-view class="p-2.5 min-h-screen" />
  </div>
</template>

<script setup>
// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;300;400;500;800&display=swap');

* {
  margin: 0;
  padding: 0;
  font-family: 'Montserrat', sans-serif;
}
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
