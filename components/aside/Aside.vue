<template>
  <div class="aside pl-4 pr-4">
    <button class="rotate-90" @click="toggleMenu">|||</button>
    <AsideMenu v-if="isOpenMenu" @close-menu="toggleMenu" />
  </div>
</template>
<script setup>
const isOpenMenu = ref(false);

const toggleMenu = () => {
  isOpenMenu.value = !isOpenMenu.value;
};
</script>
