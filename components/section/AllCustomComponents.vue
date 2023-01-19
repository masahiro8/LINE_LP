<script setup lang="ts">
import { ref } from "vue";
import HeaderText from "./header/HeaderText.vue";
import FormBannerInput from "./form-banner/FormBannerInput.vue";
import Feature1 from "./features/Feature1.vue";
import Feature2 from "./features/Feature2.vue";
import Feature3 from "./features/Feature3.vue";
import PriceText from "./pricing/PricingText.vue";
import PricingPlans from "./pricing/Pricing.vue";
import ContactText from "./contact/ContactText.vue";
import ContactForm from "./contact/Contact.vue";
</script>

<template>
  <!----Header Text----->
  <HeaderText />
  <!----Feature 1----->
  <Feature1 />
  <!----Feature 2----->
  <Feature2 />
  <!----Feature 3----->
  <Feature3 />
  <!----Form Email Banner----->
  <FormBannerInput />
  <!----Price Text----->
  <PriceText />
  <!----Pricing Plans----->
  <PricingPlans />
  <!----Contact Text ----->
  <ContactText />
  <!----Contact Form ----->
  <ContactForm />
</template>
