<template>
  <v-app>
    <v-app-bar flat class="border-b">
      <v-app-bar-title>Meu app</v-app-bar-title>
    </v-app-bar>

    <v-main>
      <v-container>
        <v-btn color="">Submit</v-btn>
        <h1 class="text-blue-lighten-2 bg-blue-darken-4">Dashboard</h1>

        <div class="d-flex flex-column flex-md-row justify-space-between">
          <div
            class="bg-grey-lighten-1 w-100 pa-4 border rounded-lg elevation-2">
            teste
          </div>
          <div
            class="w-100 pa-4 border rounded-lg elevation-2">
            teste
          </div>
          <div
          class="w-100 pa-4 border rounded-lg elevation-2 ">
          teste
          </div>
        </div>
      </v-container>
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script setup>
  import HelloWorld from '@/components/HelloWorld.vue'
</script>
