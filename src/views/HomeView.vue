<script setup lang="ts"></script>

<template>
  <main>
    <v-container class="mt-10 h-50">
        <v-row no-gutters justify="center">
          <v-col xs="12" sm="12" md="6" lg="4">
            <v-card class="pa-3 ma-3 mx-8" color="grey-darken-4">
              <v-card-title class="text-center">Basic</v-card-title>
              <p class="text-h4 text-center font-weight-bold my-5 mb-10 pricing-text"><v-icon>mdi-currency-usd</v-icon>19.99</p>
              <v-card-text class="text-center">
                <div class="mb-4"><v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon><span class="text-body-1">500 GB Storage</span></div>
                <div class="mb-4"><v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon><span class="text-body-1">2 Users Allowed</span></div>
                <div><v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon><span class="text-body-1">Send up to 3 GB</span></div> 
              </v-card-text>
              <v-card-actions>
                <v-btn color="grey-darken-4" variant="flat" block>Learn More</v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col xs="12" sm="12" md="6" lg="4">
            <v-card class="pa-3 ma-3 mx-8" color="purple-darken-4">
              <v-card-title class="text-center">Professional</v-card-title>
              <p class="text-h4 text-center font-weight-bold mt-5 mb-10 pricing-text"><v-icon>mdi-currency-usd</v-icon>24.99</p>
              <v-card-text class="text-center">
                <div class="mb-4"><v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon><span class="text-body-1">1 TB Storage</span></div>
                <div class="mb-4"><v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon><span class="text-body-1">5 Users Allowed</span></div>
                <div><v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon><span class="text-body-1">Send up to 10 GB</span></div> 
              </v-card-text>
              <v-card-actions>
                <v-btn color="deep-purple-darken-1" variant="flat" block>Learn More</v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col xs="12" sm="12" md="6" lg="4">
            <v-card class="pa-3 ma-3 mx-8" color="grey-darken-4">
              <v-card-title class="text-center">Master</v-card-title>
              <p class="text-h4 text-center font-weight-bold mt-5 mb-10 pricing-text"><v-icon>mdi-currency-usd</v-icon>39.99</p>
              <v-card-text class="text-center">
                <div class="mb-4"><v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon><span class="text-body-1">2 TB Storage</span></div>
                <div class="mb-4"><v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon><span class="text-body-1">10 Users Allowed</span></div>
                <div><v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon><span class="text-body-1">Send up to 20 GB</span></div> 
              </v-card-text>
              <v-card-actions>
                <v-btn color="grey-darken-4" variant="flat" block>Learn More</v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
    </v-container>
  </main>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&display=swap');
* {
  font-family: 'Montserrat', sans-serif !important; 
}
.pricing-text {
  font-size: 50px !important;
}
</style>