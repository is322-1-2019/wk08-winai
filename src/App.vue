<template>
  <div id="app">
    <ex01-page v-show="false" class="card"></ex01-page>
    <ex02-page v-show="false" class="card"></ex02-page>
    <ex03-page v-show="true" class="card"></ex03-page>
  </div>
</template>

<script>
import Ex01Page from "./components/ex01/Ex01Page.vue";
import Ex02Page from "./components/ex02/Ex02Page.vue";
import Ex03Page from "./components/ex03/Ex03Page.vue";

export default {
  name: 'app',
  components: {
    Ex01Page,
    Ex02Page,
    Ex03Page,
  }
}
</script>

<style>

</style>
