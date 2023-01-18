<script setup lang="ts">
import { ref } from "vue";
import { feature1 } from "@/data/CustomComponents";
</script>
<template>
  <div>
    <div class="feature1-component mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Feature 1 Text
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" md="10" lg="7">
            <div class="text-center">
              <v-chip size="small" class="bg-error" text-color="white">
                Feature 1
              </v-chip>
              <h2 class="section-title font-weight-medium">
                LINE公式アカウント活用のメリット
              </h2>
              <p class="text-muted">
                LINEの国内月間アクティブユーザーは、8300万人以上（LINE紹介資料2020年1月-6月期より）となり、多くの生活者（ユーザー）が活用するメールでのメッセージに代わるコミュニケーション手段となりました。そのため企業はLINEをマーケティングに活用することで、多くの生活者とダイレクトにコミュニケーションをとることができます。LINEで生活者とダイレクトにコミュニケーションをとるメリットは主に以下3点となります。
              </p>
            </div>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Feature 1 Text
        ----------------------------------------------- -->
        <!-- -----------------------------------------------
            Start Feature 1
        ----------------------------------------------- -->
        <v-row justify="center" class="mt-13">
          <v-col cols="12" sm="6" v-for="card in feature1" :key="card.title">
            <v-card elevation="0">
              <div>
                <div class="icon-round bg-light-info">
                  <i :class="card.icon"></i>
                </div>
                <h5 class="font-weight-medium font-18">{{ card.title }}</h5>
                <p class="my-5 text-muted pr-sm-10">{{ card.desc }}</p>
                <a
                  href="#"
                  class="text-themecolor linking text-decoration-none d-flex align-center"
                >
                  Explore More <i class="mdi mdi-arrow-right"></i>
                </a>
              </div>
            </v-card>
          </v-col>
        </v-row>
        <!-- -----------------------------------------------
            End Feature 1
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
