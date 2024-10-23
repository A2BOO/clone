<template>
  <div class="body">
    <div class="container">
      <div class="box">
        <img class="img" src="" alt="#" />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
interface Img {
  img: string;
}

const img = ref<Img>({
  img: "https://images6.alphacoders.com/136/1363478.jpeg",
});
</script>

<style scoped>
.body {
  @apply w-full h-screen flex justify-center bg-slate-700;
}

.container {
  @apply w-[1240px] bg-gray-600;
}

.box {
  @apply w-full h-[500px] bg-slate-500;
}

.img {
  @apply object-cover;
}
</style>
