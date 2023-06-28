<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
export default {
  data() {
    return {
      classe: 100
    }
  },
  components: {
    AppHeader, AppMain
  }
}

</script>

<template>
  <!-- header-->
  <AppHeader />


  <!-- main-->
  <AppMain />
</template>


<style>
h3 {
  color: rgb(231, 65, 23)
}
</style>