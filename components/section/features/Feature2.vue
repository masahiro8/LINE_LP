<script setup lang="ts">
import { ref } from "vue";
</script>
<template>
  <div>
    <div class="feature2-component">
      <v-container>
        <!-- -----------------------------------------------
            Start Feature 2 Text
        ----------------------------------------------- -->
        <v-row justify="center">
          <v-col cols="12" sm="10">
            <div class="text-center">
              <v-chip size="small" class="bg-primary" text-color="white">
                Point 2
              </v-chip>
              <h2 class="section-title font-weight-medium">
                LINEで使えるチャットボットとは？
              </h2>
              <p class="feature-text">
                チャットボットとは、「チャット（会話）」と「ボット（ロボット）」を組み合わせた言葉です。
                人が応対するのではなく、プログラムが会話を行う仕組みを「チャットボット」と呼びます。チャットボットには、シンプルな返答を行うものから、AIを搭載した高度なやりとりを行うものまで幅広くあります。
                LINE公式アカウントには、チャットボットとして使える「3つの機能」が提供されています。
              </p>
            </div>
          </v-col>
        </v-row>

        <!-- -----------------------------------------------
            End Feature 2 Text
        ----------------------------------------------- -->
        <!-- -----------------------------------------------
            Start Feature 2
        ----------------------------------------------- -->
        <v-row justify="center" class="mt-13">
          <v-col cols="12" lg="7" sm="9">
            <v-card elevation="0">
              <div class="icon-round bg-light-info"></div>
              <v-alert class="text-h5" color="primary">
                LINEのボット機能1：「応答メッセージ」</v-alert
              >
              <p class="my-5 pr-sm-10">
                「応答メッセージ」は、ユーザーから送られてきた「キーワード」に反応して、あらかじめ設定したコンテンツを自動返信する機能です。<br />

                設定するのは、以下の2点です。
              </p>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-title
                    >・反応する「キーワード」</v-list-item-title
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-title
                    >・キーワードに反応して送信する「メッセージ」</v-list-item-title
                  >
                </v-list-item-content>
              </v-list-item>
              <div class="bg-extra-light mt-5">
                <div class="pt-3 pb-6 pl-6 pr-4">
                  <v-chip class="ma-2" color="primary" text-color="white">
                    使い方の例
                  </v-chip>
                  <p class="mt-1">
                    キーワードに「セール情報」、メッセージに「今週のセール品の情報」を設定。友だちから「セール情報」というメッセージが送られてきた場合に、設定したメッセージが自動返信される。
                  </p>
                </div>
              </div>
            </v-card>
            <v-card elevation="0" class="mt-15">
              <div class="icon-round bg-light-info"></div>
              <v-alert class="text-h5" color="primary">
                LINEのボット機能2：「AI応答メッセージ」</v-alert
              >
              <p class="my-5 pr-sm-10">
                AI応答メッセージは、「キーワード」を設定せずとも、友だちから送られてきたメッセージの「タイプ」をAIが判断し、合致する情報を返信する機能です。(タイプはカテゴリーのようなイメージ)<br />
                設定するのは以下です。
              </p>
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-title
                    >・タイプごとの「メッセージ」</v-list-item-title
                  >
                </v-list-item-content>
              </v-list-item>
              <div class="bg-extra-light mt-5">
                <div class="pt-3 pb-6 pl-6 pr-4">
                  <v-chip class="ma-2" color="primary" text-color="white">
                    使い方の例
                  </v-chip>
                  <p class="mt-1">
                    タイプの「支払い方法」のメッセージを設定。友だちが支払い方法についての問い合わせを送信してきた場合、自動で支払い方法に設定したメッセージが返信される。
                  </p>
                </div>
              </div>
            </v-card>
            <v-card elevation="0" class="mt-15">
              <div class="icon-round bg-light-info"></div>
              <v-alert class="text-h5" color="primary">
                LINEのボット機能3：「Messaging API」の利用</v-alert
              >
              <p class="my-5 pr-sm-10">
                Messaging
                APIとは、LINE社が提供している仕組みで、LINEを通じたコミュニケーションを行うアプリを独自で開発することが出来るサービスです。
                MessagingAPIを利用すると、柔軟に、自由に、チャットボットの仕組みを実装することが出来ます。<br />
              </p>
              <div class="bg-extra-light">
                <div class="pa-6">
                  <p>Messaging APIを利用する場合は、</p>
                  <ol class="mt-2 pl-6">
                    <li>自社でシステム開発を行う。</li>
                    <li>
                      弊社が開発したシステムを使ってGoogle Spread
                      Sheetを用いてチャットボットの作成が行えます。知識は一切不要で簡単にボットを設定することができます。
                    </li>
                  </ol>
                </div>
              </div>
            </v-card>
          </v-col>
        </v-row>
        <!-- -----------------------------------------------
            End Feature 2
        ----------------------------------------------- -->
      </v-container>
    </div>
  </div>
</template>
