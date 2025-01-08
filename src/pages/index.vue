<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})
</script>

<template>
  <div relative min-h-100vh>
    <img h-full w-full src="../assets/bg.webp" alt="">

    <div class="email" absolute bottom-10 w-full flex justify-center>
      <div class="heartache-email" rd-2 bg-black p-2 p-x-5 text-8 color-white>
        639293382@qq.com
      </div>
    </div>
  </div>
</template>

<style scoped>
.heartache-email {
  background-color: rgb(212, 169, 224);
}
</style>
