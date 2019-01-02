<template>
  <div class="front">
    <Header/>
    <main>
      <div class="columns is-multiline">
        <Resource class="resource column is-half"/>
        <Resource class="resource column is-half"/>
        <Resource class="resource column is-half"/>
      </div>
    </main>
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import Resource from '~/components/Resource.vue'

export default {
  components: {
    Header,
    Resource
  }
}
</script>

<style lang="scss" scoped>
  ul {
    background-image: url("~static/FPObiz2.png");
    background-repeat: no-repeat;
    max-width: 60vw;
    margin: auto;
    display: grid;
    border: 1px solid yellow;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-gap: 0.5rem 1rem;
    grid-auto-rows: 250px;
  }
  li {
    border: 1px solid orange;
  }
  li:nth-child(1) {
    grid-column-start: 2;
    border: 1px solid red;
  }
</style>
