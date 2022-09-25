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
    <component :is="icon" />
    {{ title }}
  </div>
</template>

<script>
export default {
  props: ['title', 'icon'],
};
</script>
