<template lang="pug">
.home
  TitleMenu.menu
</template>

<script>
import TitleMenu from '../components/TitleMenu'
export default {
  components: {
    TitleMenu,
  },
}
</script>


<style lang="sass" scoped>
.home
  +flex-center
  padding: 2rem 1rem
  .menu
    max-width: 1280px
</style>