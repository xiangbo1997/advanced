<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="parent">
      <ul class="abc">
        <li>111111</li>
      </ul>
  <HelloWorld msg="Vite + Vue" />
    <ul class="abc">
        <li>111111</li>
      </ul>
  </div>
  <h1>22</h1>

</template>

<style scoped lang='scss'>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
// ::v-deep(p){
//   color: red;
// }
::v-deep(.abc){
  li{
    color: red;
  }
}
::v-deep(.card){
  // p{
  //   color: pink;
  // }
}

</style>
