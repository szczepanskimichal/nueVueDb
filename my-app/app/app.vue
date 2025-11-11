<script lang="ts">
import AppNavigation from './components/AppNavigation.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppNavigation,
    AppFooter
  }
}
</script>

<template>
  <NuxtRouteAnnouncer />
  <NuxtLoadingIndicator />
  <AppNavigation />
  <NuxtPage />
  <AppFooter />
</template>
