<template>
  <div class="aside-menu rounded-r pl-4">
    <button @click="$emit('closeMenu')">X</button>
    <ul>
      <li><button>page -1</button></li>
      <li><button>page -2</button></li>
      <li><button>page -3</button></li>
      <li><button>page -4</button></li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
.aside-menu {
  position: absolute;
  top: 0px;
  left: 0px;
  width: 100px;
  height: 100vh;
  // border: 1px solid red;
  background-color: #0284c7;
  z-index: 1;
}
</style>
