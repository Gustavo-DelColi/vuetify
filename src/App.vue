<template>
  <v-app theme="dark">
    <v-app-bar flat class="border-b">
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <v-app-bar-title>Meu app</v-app-bar-title>
      <template #append>
        <v-btn icon class="mr-2">
          <v-badge dot color="info">
            <v-icon icon="mdi-bell-outline"></v-icon>
          </v-badge>
        </v-btn>

        <v-avatar>
          <v-img
          cover
          src="https://www.shutterstock.com/image-vector/manta-ray-maori-style-tattoo-260nw-2275733347.jpg"></v-img>
        </v-avatar>
      </template>
    </v-app-bar>

    <v-main>
      <v-container>
        <h1>Dashboard</h1>

        <v-row>
          <v-col cols="12" sm="6" md="4" lg="3">
            <v-card flat class="border">
              <v-img
              class="align-end text-red"
              src="https://images.pexels.com/photos/8745850/pexels-photo-8745850.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
              >
                <v-card-title>Templo Maori</v-card-title>
              </v-img>

              <v-card-subtitle class="pt-3">NZ</v-card-subtitle>
              <v-card-text>
                <div>Rio vermelho</div>
                <div>Kia ri te</div>
              </v-card-text>

              <v-card-action>
                <v-btn variant="outlined" color="primary">Ver mais</v-btn>
                <v-btn prepend-icon="mdi-cart" variant="tonal" color="blue">Comprar</v-btn>
              </v-card-action>
            </v-card>
          </v-col>

          <v-col cols="12" sm="6" md="4" lg="3">
            <v-card flat class="border">
              <v-img
              class="align-end text-red"
              src="https://images.pexels.com/photos/8745850/pexels-photo-8745850.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
              >
                <v-card-title>Templo Maori</v-card-title>
              </v-img>
              <v-card-subtitle class="pt-3">NZ</v-card-subtitle>
              <v-card-text>
                <div>Rio vermelho</div>
                <div>Kia ri te</div>
              </v-card-text>
             <v-card-action>
                <v-btn variant="outlined" color="primary">Ver mais</v-btn>
                <v-btn prepend-icon="mdi-cart" variant="tonal" color="blue">Comprar</v-btn>
              </v-card-action>
            </v-card>
          </v-col>

          <v-col cols="12" sm="6" md="4" lg="3">
            <v-card flat class="border">
              <v-img
              class="align-end text-red"
              src="https://images.pexels.com/photos/8745850/pexels-photo-8745850.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
              >
                <v-card-title>Templo Maori</v-card-title>
              </v-img>
              <v-card-subtitle class="pt-3">NZ</v-card-subtitle>
              <v-card-text>
                <div>Rio vermelho</div>
                <div>Kia ri te</div>
              </v-card-text>
              <v-card-action>
                <v-btn variant="outlined" color="primary">Ver mais</v-btn>
                <v-btn prepend-icon="mdi-cart" variant="tonal" color="blue">Comprar</v-btn>
              </v-card-action>
            </v-card>
          </v-col>

          <v-col cols="12" sm="6" md="4" lg="3">
            <v-card flat class="border">
              <v-img
              class="align-end text-red"
              src="https://images.pexels.com/photos/8745850/pexels-photo-8745850.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
              >
                <v-card-title>Templo Maori</v-card-title>
              </v-img>
              <v-card-subtitle class="pt-3">NZ</v-card-subtitle>
              <v-card-text>
                <div>Rio vermelho</div>
                <div>Kia ri te</div>
              </v-card-text>
              <v-card-action>
                <v-btn variant="outlined" color="primary">Ver mais</v-btn>
                <v-btn prepend-icon="mdi-cart" variant="tonal" color="blue">Comprar</v-btn>
              </v-card-action>
            </v-card>
          </v-col>

        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup>
  import HelloWorld from '@/components/HelloWorld.vue'
</script>
