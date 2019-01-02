<template>
  <div class="about">
    <main class="content">
      <blockquote class="quote">Hi, I'm Bhubanjyoti Bhattacharya, but you can call me Dr. B!</blockquote>
      <p>I am a particle phenomenologist and a dedicated educator in Detroit, Michigan. My recent work focuses on the physics of heavy and light quarks, the Higgs boson, as well as dark matter.</p>
      <p>I earned a bachelor's degree in physics at Presidency College (now called Presidency University) in my hometown of Kolkata, India (2004), a master's degree in physics at the Indian Institute of Technology, Kanpur, India (2006), and a PhD
      in physics at the University of Chicago (2011).</p>
      <p>After earning my degrees, I spent a few years as a postdoctoral researcher at the University of Montreal in Canada, and then at Wayne State University in Detroit, Michigan.</p>
      <p>I joined Lawrence Technological University's Department of Natural Sciences as an Assistant Professor in 2017. Here, I teach undergraduate physics courses to science and engineering majors.</p>
      <p>When I am not playing with data or exploring theories beyond the Standard Model of particle physics, I enjoy volunteering with The Children's Center in Detroit, taking road trips with my spouse, and hanging out on the couch with my pet
      greyhound.</p>
    </main>
  </div>
</template>

<script>

export default {
  props: {
    pageTitle: {
      type: String,
      required: true
    }
  },
  data () {
    pageTitle: 'About Dr. B'
  }

}
</script>

<style lang="scss" scoped>
  main {
    border: 1px solid orange;
  }
</style>
