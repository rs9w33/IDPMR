<template>
  <v-app>
    <app-header title="IDPMR" theme="dark" />

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import AppHeader from "@/components/AppHeader/AppHeader.vue";

export default {
  components: {
    AppHeader,
  },
};
</script>
