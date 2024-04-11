<script>

    import AppHeader from './components/header/AppHeader.vue';
    import AppDaFare from './components/main/AppDaFare.vue';
    import AppSectionBlue from './components/main/AppSectionBlue.vue';
    
    export default {
      components: {
        AppHeader,
        AppDaFare,
        AppSectionBlue,
      }
    }

</script>

<template>
  
  <AppHeader></AppHeader>

    <main>

      <AppDaFare></AppDaFare>
      <AppSectionBlue></AppSectionBlue>

    </main>

</template>

<style>

</style>
