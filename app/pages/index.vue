<template>
  <div>
    <h1>WELCOME TO MY NUXT APP</h1>


  </div>

  <v-row>
    <v-col cols="12" md="3">
      <v-card height="120" color="blue">
        <v-card-text>
          <v-row>
            <v-col cols="6"> <v-icon size="100">mdi-bank</v-icon></v-col>
            <v-col cols="6">
              <v-row>
                <v-col cols="12" class="text-left">Amount</v-col>
                <v-col cols="12" class="text-left" size="100">₱1,000,000</v-col>
              </v-row>
            </v-col>
          </v-row>

        </v-card-text>
      </v-card>
    </v-col>
    <v-col cols="12" md="3">
      <v-card height="120" color="red"></v-card>
    </v-col>
    <v-col cols="12" md="3">
      <v-card height="120" color="green"></v-card>
    </v-col>
    <v-col cols="12" md="3">
      <v-card height="120" color="purple"></v-card>
    </v-col>
    <v-col cols="12" md="3">
      <v-card height="120" color="purple"></v-card>
    </v-col>
  </v-row>

</template>

<script lang="ts" setup>

</script>

<style></style>