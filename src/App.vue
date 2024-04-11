<script>

    import AppHeader from './components/header/AppHeader.vue';
    import AppDaFare from './components/main/AppDaFare.vue';
    import AppSectionBlue from './components/main/AppSectionBlue.vue';
    import AppInfoContacts from './components/footer/AppInfoContacts.vue';
    import AppRegistrati from './components/footer/AppRegistrati.vue';


    export default {
      components: {
        AppHeader,
        AppDaFare,
        AppSectionBlue,
        AppInfoContacts,
        AppRegistrati

        
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
      <AppInfoContacts></AppInfoContacts>
      <AppRegistrati></AppRegistrati>
    </footer>



</template>

<style>

</style>
