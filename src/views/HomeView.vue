<script setup lang="ts">
import { ref } from "vue";
const isEnabled = ref(false)
</script>

<template>
  <main>
    <p class="text-center mt-10 bod-title">Our Pricing</p>
    <v-switch color="purple" class="switch-center mt-4" v-model="isEnabled">
      <template v-slot:label>
        <span class="switch-label">Annual</span>
      </template>
    </v-switch>
    <v-container class="mt-6 h-50">
      <!-- Yearly Prices -->
      <v-row no-gutters justify="center" v-if="isEnabled">
        <v-col sm="12" md="6" lg="4">
          <v-card class="pa-3 ma-3 mx-8" color="grey-darken-4">
            <v-card-title class="text-center">Basic</v-card-title>
            <p class="text-h4 text-center font-weight-bold my-10 pricing-text">$199.99</p>
            <v-divider class="mb-6"></v-divider>
            <v-card-text class="text-center">
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">500 GB Storage</span>
              </div>
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">2 Users Allowed</span>
              </div>
              <div>
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">Send up to 3 GB</span>
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn color="grey-darken-4" variant="flat" block>Learn More</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col sm="12" md="6" lg="4">
          <v-card class="pa-3 ma-3 mx-8" color="purple-darken-4">
            <v-card-title class="text-center">Professional</v-card-title>
            <p class="text-h4 text-center font-weight-bold my-10 pricing-text">$249.99</p>
            <v-divider class="mb-6"></v-divider>
            <v-card-text class="text-center">
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">1 TB Storage</span>
              </div>
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">5 Users Allowed</span>
              </div>
              <div>
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">Send up to 10 GB</span>
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn color="deep-purple-darken-1" variant="flat" block>Learn More</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col sm="12" md="6" lg="4">
          <v-card class="pa-3 ma-3 mx-8" color="grey-darken-4">
            <v-card-title class="text-center">Master</v-card-title>
            <p class="text-h4 text-center font-weight-bold my-10 pricing-text">$399.99</p>
            <v-divider class="mb-6"></v-divider>
            <v-card-text class="text-center">
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">2 TB Storage</span>
              </div>
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">10 Users Allowed</span>
              </div>
              <div>
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">Send up to 20 GB</span>
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn color="grey-darken-4" variant="flat" block>Learn More</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
      <!-- Monthly Prices -->
      <v-row no-gutters justify="center" v-if="!isEnabled">
        <v-col sm="12" md="6" lg="4">
          <v-card class="pa-3 ma-3 mx-8" color="grey-darken-4">
            <v-card-title class="text-center">Basic</v-card-title>
            <p class="text-h4 text-center font-weight-bold my-10 pricing-text">$19.99</p>
            <v-divider class="mb-6"></v-divider>
            <v-card-text class="text-center">
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">500 GB Storage</span>
              </div>
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">2 Users Allowed</span>
              </div>
              <div>
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">Send up to 3 GB</span>
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn color="grey-darken-4" variant="flat" block>Learn More</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col sm="12" md="6" lg="4">
          <v-card class="pa-3 ma-3 mx-8" color="purple-darken-4">
            <v-card-title class="text-center">Professional</v-card-title>
            <p class="text-h4 text-center font-weight-bold my-10 pricing-text">$24.99</p>
            <v-divider class="mb-6"></v-divider>
            <v-card-text class="text-center">
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">1 TB Storage</span>
              </div>
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">5 Users Allowed</span>
              </div>
              <div>
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">Send up to 10 GB</span>
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn color="deep-purple-darken-1" variant="flat" block>Learn More</v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
        <v-col sm="12" md="6" lg="4">
          <v-card class="pa-3 ma-3 mx-8" color="grey-darken-4">
            <v-card-title class="text-center">Master</v-card-title>
            <p class="text-h4 text-center font-weight-bold my-10 pricing-text">$39.99</p>
            <v-divider class="mb-6"></v-divider>
            <v-card-text class="text-center">
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">2 TB Storage</span>
              </div>
              <div class="mb-4">
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">10 Users Allowed</span>
              </div>
              <div>
                <v-icon class="ma-2" color="green-accent-4">mdi-star-four-points</v-icon
                ><span class="text-body-1">Send up to 20 GB</span>
              </div>
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
  font-size: 70px !important;
}
.bod-title {
  font-size: 40px !important;
}
.switch-center {
  display: flex;
  justify-content: center;
}
.switch-label {
  font-size: 20px !important;
}
</style>
