<template>
  <di class="flex gap-[40px]">
    <div class="">
      <img :src="`/_nuxt/assets/images/${icon}`" alt="" />
    </div>

    <div class="max-w-[450px]">
      <h3 class="font-semibold text-[20px] leading-[30px] text-[#0F1826]">
        {{ title }}
      </h3>
      <p class="text-[14px] leading-[20px] text-[#607987] my-[14px]">
        {{ text }}
      </p>
    </div>
  </di>
</template>
<script setup>
const props = defineProps(["id", "icon", "title", "text"]);
</script>
<style lang="scss"></style>
