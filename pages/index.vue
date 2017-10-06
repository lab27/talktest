<template lang="pug">
  section.container(:class="{active: active}")
    p I'm raddddd
    button(@click="active = !active") hello
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  data () {
    return {
      active: false
    }
  }
}
</script>

<style lang="scss" scoped>
@import '../docs/assets/css/home.scss';
</style>
