<script setup lang="ts">
import { ref } from "vue";
import { feature3 } from "@/data/CustomComponents";
</script>
<template>
  <div>
    <div class="feature1-component mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Feature 3 Text
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" sm="10">
            <div class="text-center">
              <v-chip size="small" class="bg-primary" text-color="white">
                Point 3
              </v-chip>
              <h2 class="section-title font-weight-medium">
                LINEでチャットボットを利用するメリット
              </h2>
              <p class="feature-text">
                LINEでのチャットボット利用には、以下のようなメリットがあります。
              </p>
            </div>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Feature 3 Text
        ----------------------------------------------- -->
        <!-- -----------------------------------------------
            Start Feature 3
        ----------------------------------------------- -->
        <v-row justify="center" class="mt-13 mx-5">
          <v-col cols="12" sm="4" v-for="card in feature3" :key="card.title">
            <v-card elevation="0">
              <div>
                <div class="icon-round bg-light-info">
                  <i :class="card.icon"></i>
                </div>
                <h5 class="font-weight-medium font-18">{{ card.title }}</h5>
                <p class="my-5 text-muted">{{ card.desc }}</p>
              </div>
            </v-card>
          </v-col>
        </v-row>
        <!-- -----------------------------------------------
            End Feature 3
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
