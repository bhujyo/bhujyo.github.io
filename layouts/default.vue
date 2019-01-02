<template>
  <div class="nuxt-wrapper">
    <div class="layout-wrapper">
      <Header pageTitle="pageTitle" />
      <div class="bb-nav-page columns">
        <Nav class="column is-one-third"/>
        <nuxt class="column"/>
      </div>
    </div>
  </div>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Header from '~/components/Header.vue'

export default {
  components: {
    Nav,
    Header
  },
  props: {
    pageTitle: {
      type: String,
      required: true
    }
  }

}
</script>

<style lang="scss" scoped>

</style>
