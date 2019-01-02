<template lang="html">
  <section class="bb-header columns is-mobile">
    <div class="column is-one-third">
      <figure
        class="image honeycomb">
        <img
          src="~static/bBhattacharya1.jpg"
          alt="Profile of Bhubanjyoti Bhattacharya">
      </figure>
    </div>
    <div class="hero column is-two-thirds">
      <div class="hero-body">
        <h1 class="title is-1 has-text-centered">{{ pageTitle }}</h1>
      </div>
    </div>
  </section>
</template>

<script>

export default {
  props: {
    pageTitle: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang="scss" scoped>
  .bb-header {
    align-items: center;
  }
  .honeycomb {
    width: 100%;
    clip-path: polygon(0 75%, 50% 100%, 100% 75%, 100% 25%, 50% 0, 0 25%);
    img {
      height: 100%;
    }
  }

</style>
