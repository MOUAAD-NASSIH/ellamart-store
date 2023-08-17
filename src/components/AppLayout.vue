<script setup>
import { ref } from 'vue'

const drawer = ref(true)
</script>

<template>
  <div class="layout">
    <v-layout>
      <v-navigation-drawer v-model="drawer" location="right">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni ducimus, odio non facere
          dolorem quae sit totam quos delectus impedit eius tempore, accusamus corporis reiciendis
          quasi, similique voluptatum explicabo et.
        </p>
      </v-navigation-drawer>
      <v-app-bar>
        <v-app-bar-nav-icon @click="drawer = true"></v-app-bar-nav-icon>
      </v-app-bar>
      <v-footer :app="true">
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eligendi natus soluta eaque,
          molestiae accusamus numquam aliquid velit quae est praesentium voluptatum, quo ipsum
          distinctio, incidunt asperiores voluptates architecto error dolore!
        </p>
      </v-footer>
    </v-layout>
  </div>
</template>

<style lang="scss" scoped></style>
