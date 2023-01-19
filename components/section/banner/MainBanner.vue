<template>
  <div class="banner-wrapper">
    <v-container>
      <!-- -----------------------------------------------
            Start Banner
        ----------------------------------------------- -->
      <v-row justify="center">
        <v-col cols="12" sm="7" lg="6" class="d-flex align-center">
          <div class="pl-10 text-sm-left text-center">
            <h1 class="banner-title font-weight-bold text-white">
              LINE公式アカウント<br />登録代行・運用サポート
            </h1>
            <h4
              class="banner-subtitle white--text font-weight-regular text-white"
            >
              まずはお気軽にご相談ください！
            </h4>
            <div class="mt-md-16 mt-10 d-sm-flex d-block">
              <v-btn
                color="blue"
                class="mr-0 mr-sm-5 mb-5 mb-sm-0 btn-custom-md d-sm-flex d-block btn-100"
                size="large"
                flat
              >
                <NuxtLink
                  to=""
                  target="_blank"
                  class="text-decoration-none text-white font-weight-bold"
                >
                  お問合せ
                </NuxtLink>
              </v-btn>
            </div>
          </div>
        </v-col>
        <v-col cols="12" sm="5" lg="6">
          <img
            src="/images/landingpage/banner-img.png"
            alt="banner"
            class="img-fluid"
          />
        </v-col>
      </v-row>

      <!-- -----------------------------------------------
            End Banner
        ----------------------------------------------- -->
    </v-container>
  </div>
</template>
