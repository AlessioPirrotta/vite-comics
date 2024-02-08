<script >
import AppHeader from './components/AppHeader.vue'
import AppContents from './components/AppContents.vue'
import AppShop from './components/AppShop.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default{
  components:{
    AppHeader,
    AppContents,
    AppShop,
    AppMain,
    AppFooter
  }
}
</script>

<template>
  <AppHeader/>
  <AppContents/>
  <AppShop/>
  <AppMain/>
  <AppFooter/>
</template>

<style lang="scss" >
@use './style/general.scss' as *;
</style>
