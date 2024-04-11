<script>

    import AppHeader from './components/header/AppHeader.vue';
    import AppDaFare from './components/main/AppDaFare.vue';
    import AppSectionBlue from './components/main/AppSectionBlue.vue';
    import AppRegistrati from './components/footer/AppRegistrati.vue';


    export default {
      components: {
        AppHeader,
        AppDaFare,
        AppSectionBlue,
        AppRegistrati,

        
      }
    }

</script>

<template>
  
  <AppHeader></AppHeader>

    <main>
      <AppDaFare></AppDaFare>
      <AppSectionBlue></AppSectionBlue>
    </main>

    <footer>
      <AppRegistrati></AppRegistrati>
    </footer>



</template>

<style>

</style>
