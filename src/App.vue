<script >
import AppHeader from './components/AppHeader.vue'
import AppContents from './components/AppContents.vue'
import AppShop from './components/AppShop.vue'

export default{
  components:{
    AppHeader,
    AppContents,
    AppShop
  }
}
</script>

<template>
  <AppHeader/>
  <AppContents/>
  <AppShop/>
</template>

<style lang="scss" >
@use './style/general.scss' as *;


</style>
