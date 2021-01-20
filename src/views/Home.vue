<template>
  <div class="home">
    <img class="bg" src="./../assets/bg.jpg" alt="">
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({
  components: {
  },
})
export default class Home extends Vue {}
</script>
<style lang="css">
  .bg {
    width: 150px;
    height: auto;
  }
</style>
