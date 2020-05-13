<template>
  <div class="mainmenu">
    <nav class="mainmenu__nav">
      <ul class="mainmenu__list">
        <li class="mainmenu__list-item">
          <nuxt-link to="/works">works</nuxt-link>
        </li>
        <li class="mainmenu__list-item">
          <nuxt-link to="/contact">contact</nuxt-link>
        </li>
        <li class="mainmenu__list-item">
          <nuxt-link to="/about">about</nuxt-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'AppMenu'
}
</script>
