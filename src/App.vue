<script >
import AppHeader from './components/AppHeader.vue'
import AppContents from './components/AppContents.vue'
import AppShop from './components/AppShop.vue'
import AppMain from './components/AppMain.vue'

export default{
  components:{
    AppHeader,
    AppContents,
    AppShop,
    AppMain
  }
}
</script>

<template>
  <AppHeader/>
  <AppContents/>
  <AppShop/>
  <AppMain/>
</template>

<style lang="scss" >
@use './style/general.scss' as *;
</style>
