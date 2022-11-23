<script setup>
import AppHeader from "../components/AppHeader.vue"
import AppList from "../components/AppList.vue"
import AppFooter from "../components/AppFooter.vue"
</script>

<template>
  <main>
    <AppHeader>
      :title="info.label"
      :description="info.description"
    </AppHeader>

    <AppList>

    </AppList>
    <AppFooter></AppFooter>
  </main>
</template>
