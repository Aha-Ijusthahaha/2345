<script setup>
import Notice from './components/Notice.vue';
import Header from './components/Header.vue'
import Main from './components/Main.vue';
</script>

<template>
  <div id="sticky">
    <Notice></Notice>
    <Header></Header>
  </div>
  <Main></Main>
</template>

<style scoped>
@import url('https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css');

#sticky {
  position: sticky;
  top: 0;
  z-index: 9999;
}
</style>