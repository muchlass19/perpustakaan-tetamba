<template>
  <v-app-bar
      :collapse="!collapseOnScroll"
      :collapse-on-scroll="collapseOnScroll"
      absolute
      color="#3f51b5"
      dark
      scroll-target="#scroll"
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Collapsing Bar</v-toolbar-title>

      <v-spacer></v-spacer>
    </v-app-bar>
    
</template>

<script>
  export default {
    data: () => ({
      collapseOnScroll: true,
    }),
  }
</script>