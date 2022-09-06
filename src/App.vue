<template>
  <div id="app">
    <SidebarComponent/>
    <MainHeader/>
    <MainFooter/>
  </div>
</template>

<script>
import SidebarComponent from './components/SidebarComponent.vue'
import MainHeader from './components/MainHeader.vue'
import MainFooter from './components/MainFooter.vue'


export default {
  name: 'App',
  components: {
    SidebarComponent,
    MainHeader,
    MainFooter,
}
}
</script>

<style scoped>

</style>
