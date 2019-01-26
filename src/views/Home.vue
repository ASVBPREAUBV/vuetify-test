<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Test msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Test from '@/components/Test.vue'; // @ is an alias to /src

@Component({
  components: {
    Test,
  },
})
export default class Home extends Vue {}
</script>
