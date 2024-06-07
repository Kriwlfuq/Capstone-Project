<script setup>
import loginAdmin from './pages/login/loginAdmin.vue'
import LoginParent from './pages/login/loginParent.vue'
import LoginStudent from './pages/login/loginStudent.vue'


</script>

<template>
  <div>
    <a href="" target="">
      <img src="" class="logo" alt="" />
    </a>
    <a href="" target="">
      <img src="" class="logo vue" alt="" />
    </a>
  </div>
  <Login msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #ee0b0baa);
}
</style>
