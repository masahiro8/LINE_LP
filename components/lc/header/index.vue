<script setup lang="ts">
import { ref } from "vue";
const drawer = ref(null);
</script>
<template>
  <div>
    <!-- -----------------------------------------------
          Start Header
    ----------------------------------------------- -->
    <v-app-bar class="app-header pt-lg-0 pt-3" absolute flat elevate-on-scroll>
      <v-container class="fill-height">
        <v-toolbar class="bg-transparent d-flex align-center">
          <!-- Logo -->
          <LcLogoBackhamLogo />
          <!-- Desktop view Navigation -->
          <div
            class="navigation ml-auto d-lg-block"
            v-bind:class="[isActive ? 'd-block' : '']"
            @click="isActive = !isActive"
          ></div>
          <v-app-bar-nav-icon
            width="30"
            class="d-md-none d-sm-flex ml-auto drawer-icon text-white mr-0"
            @click.stop="drawer = !drawer"
          ></v-app-bar-nav-icon>
        </v-toolbar>
      </v-container>
    </v-app-bar>
    <!-- -----------------------------------------------
          End Header
    ----------------------------------------------- -->
  </div>
  <!----sidebar menu drawer start----->
  <v-navigation-drawer v-model="drawer" temporary>
    <ul class="navbar-nav py-4">
      <li class="nav-item mb-3">
        <NuxtLink class="nav-link text-dark py-0" to="/">
          Custom Components
        </NuxtLink>
      </li>
      <li class="nav-item mb-4">
        <NuxtLink class="nav-link text-dark py-0" to="/basic-components"
          >Basic Components</NuxtLink
        >
      </li>
      <li class="nav-item ml-3 mr-3">
        <!-- login-regiter -->
        <v-btn color="error" block flat>
          <NuxtLink
            to=""
            target="_blank"
            class="text-decoration-none text-white"
            >お問合せ</NuxtLink
          >
        </v-btn>
      </li>
    </ul>
  </v-navigation-drawer>
</template>
