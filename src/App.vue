<script>

    import AppHeader from './components/header/AppHeader.vue';
    import AppCard from './components/main/AppCard.vue';
    import SingleCard from './components/main/SingleCard.vue';
    import AppSectionBlue from './components/main/AppSectionBlue.vue';
    import AppInfoContacts from './components/footer/AppInfoContacts.vue';
    import AppRegistrati from './components/footer/AppRegistrati.vue';


    export default {
      components: {
        AppHeader,
        AppCard,
        SingleCard,
        AppSectionBlue,
        AppInfoContacts,
        AppRegistrati
    
      }
    }

</script>

<template>
  
  <AppHeader></AppHeader>

    <main>
      <AppCard></AppCard>
      <AppSectionBlue></AppSectionBlue>
    </main>

    <footer>
      <AppInfoContacts></AppInfoContacts>
      <AppRegistrati></AppRegistrati>
    </footer>



</template>

<style>

</style>
