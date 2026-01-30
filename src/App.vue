<template>
  <v-app>
    <v-navigation-drawer permanent>
      <v-list>
        <v-list-item title="Dashboard" prepend-icon="mdi-view-dashboard" />
        <v-list-item title="Users" prepend-icon="mdi-account-group" />
        <v-list-item title="Settings" prepend-icon="mdi-cog" />
      </v-list>
    </v-navigation-drawer>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script setup lang="ts">
</script>
