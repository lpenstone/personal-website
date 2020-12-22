<template>
  <div class="combo__img" :class="landscape ? 'combo__img--landscape' : 'combo__img--portrait'">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'Combo-Img',
  data () {
    return {}
  },
  props: {
    landscape: {
      type: Boolean,
      default: false
    }
  }
}
</script>

<style scoped lang="stylus" src="./Combo-Img.styl">