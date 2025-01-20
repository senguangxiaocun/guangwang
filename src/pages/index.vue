<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div relative min-h-100vh>
    <img h-full w-full src="../assets/bg.webp" alt="">

    <div class="email" absolute bottom-10 w-full flex justify-center>
      <div class="your_style" rd-2 bg-black p-2 p-x-5 text-8 color-white>
        weiyunjian0203@icloud.com
      </div>
    </div>
  </div>
</template>

<style scoped>
.your_style {
  background-color: rgb(238, 55, 130);
  color: rgb(255, 255, 255);
}
</style>
