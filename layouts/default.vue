<template>
  <div class="view-wrap" :class="darkMode ? 'mode--dark' : ''">
    <div class="view-content">
      <x-nav></x-nav>
      <Nuxt />
      <x-section as="alt" size="sm" id="footer">
        <x-content>
          <div class="footer__wrap">
            <div class="footer--left">
              <span class="font-size--sm">©2020 Laura Penstone</span>
              <!-- <p class="font-size--sm">Built with <x-link href="https://www.stylx.dev" target="_blank">Stylx</x-link></p> -->
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