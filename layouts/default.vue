<template>
  <div class="view-wrap" :class="darkMode ? 'mode--dark' : ''">
    <div class="view-content">
      <x-nav>
        <template v-slot:links>
          <ul>
            <li>
              <x-link as="link-alt" :to="{name: 'resume'}">Resume</x-link>
            </li>
            <li>
              <x-link as="link-alt" :to="{name: 'art'}">Art</x-link>
            </li>
            <li>
              <x-link as="link-alt" href="https://www.etsy.com/ca/shop/LPDesignsCanada" target="_blank">Shop</x-link>
            </li>
          </ul>
        </template>
      </x-nav>
      <Nuxt />
      <x-section as="alt" size="sm" id="footer">
        <x-content>
          <div class="footer__wrap">
            <div class="footer--left">
              <span class="font-size--sm">©2022 Laura Penstone</span>
            </div>
            <div class="footer--right">
              <x-social></x-social>
            </div>
          </div>
        </x-content>
      </x-section>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Layout',
  data () {
    return {}
  },
  computed: {
    darkMode: function () {
      return this.$store.state.darkMode
    }
  },
  watch: {
    $route () {
      this.$store.commit('toggleMenu', false)
    }
  }
}
</script>

<style scoped lang="stylus">

.view-wrap
  .view-content
    min-height: 90vh

.footer__wrap
  display: flex
  justify-content: space-between
  align-items: center

  @media(max-width: 767px)
    text-align: center
    flex-direction: column

</style>