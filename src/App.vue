<template>
  <div>
    <web-headear></web-headear>
    <router-view></router-view>
    <web-footer></web-footer>
  </div>
</template>

<script setup>
import HomePage from "./components/pages/HomePage.vue";
import WebHeadear from "./components/header/WebHeadear.vue";
import WebFooter from "./components/footer/WebFooter.vue";
</script>
