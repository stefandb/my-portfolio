<template>
  <div
    class="
      px-2
      py-2
      rounded-lg
      flex
      items-center
      justify-center
      shadow-xl
      border-2
      text-black
      dark:text-white
    "
  >
    f{{ title }}f
  </div>
</template>

<script>
export default {
  props: ['title'],
};
</script>
