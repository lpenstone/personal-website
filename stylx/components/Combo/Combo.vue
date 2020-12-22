<template>
  <div class="combo__wrap" :class="['combo__wrap--' + asClass, 'combo__wrap--' + size, {'combo__wrap--center': isCenter}]">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'Combo',
  props: {
    as: {
      type: String,
      default: 'standard'
    },
    size: {
      type: String,
      default: 'md'
    }
  },
  data () {
    return {}
  },
  computed: {
    isCenter: function () {
      return this.as.indexOf('center') > -1
    },
    asClass: function () {
      if (this.as.indexOf('-center') > -1) {
        return this.as.replace('-center', '')
      }
      return this.as
    }
  }
}
</script>

<style scoped lang="stylus" src="./Combo.styl">