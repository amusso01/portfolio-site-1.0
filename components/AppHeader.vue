<template>
  <header class="header">
    <h1 class="header__logo">andrea musso</h1>
    <AppMenu />
  </header>
</template>

<script>
import AppMenu from '@/components/AppMenu'

export default {
  name: 'AppHeader',
  components: {
    AppMenu
  }
}
</script>
