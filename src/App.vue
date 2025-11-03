<template>
  <v-app>
    <v-main>
      <v-tooltip text="Tooltip text should be white, background color should be red">
        <template v-slot:activator="{ props }">
          <v-btn v-bind="props">Hover Over Me</v-btn>
        </template>
      </v-tooltip>
    </v-main>
  </v-app>
</template>

<script setup lang="ts">

//
</script>
