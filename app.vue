<template>
  <AppProvider :i18n="locales">
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </AppProvider>
</template>
<script setup>
import locales from "@ownego/polaris-vue/dist/locales/en.json";
</script>
