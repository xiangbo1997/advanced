<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
 

  <div class="children">
      <ul class="abc">
        <li>111111</li>
      </ul>
    <ul class="abc">
        <li>111111</li>
      </ul>
  </div>

 

</template>

<style scoped lang="scss">
// .read-the-docs{
//   color:yellow;
// }
</style>
