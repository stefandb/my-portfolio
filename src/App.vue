<template>
  <div
    class="
      w-full
      min-h-screen
      bg-white
      text-black
      dark:bg-black dark:text-white
    "
  >
    <div class="w-full p-8 flex justify-between">
      <div>
        <!-- Start LOGO -->
        <div class="font-Rampart text-3xl md:text-4xl">Stefan de bruin</div>
        <!-- End LOGO -->
      </div>

      <div
        class="flex flex-row space-x-4 font-mono text-white text-sm font-bold"
      >
        <Button title="Projects" />
        <Button button-label="About" />

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
          "
        >
          <SunIcon class="h-6 w-6 text-black dark:text-white" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { MoonIcon, SunIcon } from '@heroicons/vue/24/solid';
import Button from './Components/Navbar/Button.vue';
export default {
  components: {
    MoonIcon,
    SunIcon,
    Button,
  },
};
</script>
