<script setup>
defineProps({ slim: Boolean });
</script>
<template>
  <div
    :class="slim ? 'px:0 md:px-4' : 'px-4'"
    class="max-w-[890px] mx-auto overflow-hidden"
  >
    <slot />
  </div>
</template>
