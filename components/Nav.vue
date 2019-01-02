<template lang="html">
  <section class="bb-nav content">
    <ul class="nav-links">
      <li class="has-text-centered bg-grey04">
        <nuxt-link
          class="has-text-white"
          to="/">Home
        </nuxt-link>
      </li>
      <li class="has-text-centered bg-grey05">
        <nuxt-link
          class="is-large has-text-white has-text-centered"
          to="/about">About
        </nuxt-link>
      </li>
      <li class="has-text-centered bg-grey06">
        <nuxt-link
          class="is-large has-text-white has-text-centered"
          to="/cv">CV
        </nuxt-link>
      </li>
      <li class="has-text-centered bg-grey07">
        <nuxt-link
          class="is-large has-text-white has-text-centered"
          to="/publications">Selected Works
        </nuxt-link>
      </li>
      <li class="has-text-centered bg-grey08">
        <nuxt-link
          class="is-large has-text-white has-text-centered"
          to="/teaching">Teaching
        </nuxt-link>
      </li>
    </ul>
  </section>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style lang="scss" scoped>
  .bb-nav {
    .nav-links {
      display: flex;
      flex-direction: column;
      justify-content: flex-start;
      align-items: center;
      padding: 0 2rem;
      margin: 0;

      li {
        list-style: none;
        padding: 2rem;
        width: 100%;
        margin: .5rem 0;
        clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%);

        a {
          padding: 1rem;
        }
      }
    }
  }
</style>
