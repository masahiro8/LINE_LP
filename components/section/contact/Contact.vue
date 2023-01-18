<template>
  <div>
    <div class="mini-spacer">
      <v-container>
        <!-- -----------------------------------------------
            Start Contact Form
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" md="8">
            <div>
              <h4 class="font-weight-medium contact-title mt-0">
                Quick Contact
              </h4>
              <form>
                <v-row class="mt-7">
                  <v-col cols="12" md="6" class="py-0">
                    <v-text-field
                      label="Name"
                      variant="outlined"
                      color="primary"
                      placeholder="Name"
                    ></v-text-field>
                  </v-col>
                  <v-col cols="12" md="6" class="py-0">
                    <v-text-field
                      label="Email"
                      variant="outlined"
                      type="email"
                      color="primary"
                      placeholder="Email"
                    ></v-text-field>
                  </v-col>
                  <v-col cols="12" class="py-0">
                    <v-textarea
                      name="message"
                      color="primary"
                      variant="outlined"
                      label="Message"
                      rows="3"
                    ></v-textarea>
                  </v-col>
                </v-row>
                <v-btn
                  to="/"
                  class="btn-danger-gradient mt-7 px-8 py-2"
                  variant="outlined"
                  flat
                  color="white"
                >
                  送信
                </v-btn>
              </form>
            </div>
          </v-col>
          <v-col cols="12" md="4">
            <div class="bg-primary contact-detail-card">
              <h2 class="detail-title font-weight-medium text-white">
                バッカム株式会社
              </h2>
              <p class="op-8 mb-8 text-white">info@wrappixel.com</p>
              <p class="mt-7 op-8 mb-0 text-white">〒901-2131</p>
              <p class="op-8 mb-0 text-white">沖縄県浦添市牧港３丁目２２−５</p>
            </div>
          </v-col>
        </v-row>
        <!-- -----------------------------------------------
            End Contact Form
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
