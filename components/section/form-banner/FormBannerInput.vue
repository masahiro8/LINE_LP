<template>
  <div>
    <div class="formbanner1-component mini-spacer bg-extra-light">
      <v-container>
        <!-- -----------------------------------------------
            Start Form Banner1
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" sm="7" lg="5" class="d-flex align-center">
            <div class="text-center text-sm-left">
              <h2 class="formbanner1-title font-weight-bold">
                配信コンテンツの制作、レポートの作成等、一連の運用をサポートしています。
              </h2>
              <p class="mt-6 pt-4 text-muted">
                まずはお気軽にお問い合わせください。お客様にあったご提案をさせていただきます。
              </p>
              <div class="mt-6 pt-2">
                <form>
                  <div class="stylish-input-group">
                    <v-text-field
                      placeholder="メールアドレスを入力ください"
                      variant="solo"
                      hide-details
                    ></v-text-field>
                    <v-btn
                      rounded
                      color="primary"
                      elevation="0"
                      class="text-uppercase font-weight-medium"
                      dark
                    >
                      Get Started
                    </v-btn>
                  </div>
                </form>
              </div>
            </div>
          </v-col>
          <v-col cols="12" sm="5" lg="6" class="ml-auto">
            <img
              src="/images/form-banner/form-banner1.png"
              alt="banner"
              class="img-fluid"
            />
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Form Banner1
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
