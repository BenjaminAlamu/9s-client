<template>
  <div class="flex mb-4">
    
      <div class="w-full p-2 text-center">
        <img
          class="object-contain m-auto h-64 w-full"
          src="https://res.cloudinary.com/dldd8ucby/image/upload/v1561331855/Bitmap_1.png"
          alt="Event"
        >
        <p class="font-bold">Simi London Concert</p>
        <p class="font-semibold opacity-50">June 24th 2019 | 1700hrs GMT</p>
      </div>
    
  </div>
</template>

<script>
  import Bus from "../helpers/bus.js";
  export default {
    mounted() {
      Bus.$emit("register.trigger", true)
    }
  };
</script>

<style scoped>
</style>
