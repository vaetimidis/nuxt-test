<template>
  <v-app-bar app class="fixed-header">
    <v-toolbar-title>Title</v-toolbar-title>
  </v-app-bar>
</template>

<style scoped lang="scss">
.fixed-header {
  position: fixed !important;
  top: 0;
  width: 100%;
  z-index: 1000;
}
</style>
