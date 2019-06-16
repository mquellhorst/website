<template>
  <div>
    <front-header />
    <posts />
    <section class="section container has-text-centered">
    <div class="columns">
      <div class="column is-one-third">
        <div class="box">
          <h4>Product Design</h4>
          <ul>
            <li>Strategy & Concept</li>
            <li>User Experience Design</li>
            <li>Brand and Visual Identity</li>
          </ul>
        </div>
      </div>
      <div class="column is-one-third">
        <div class="box">
          <h4>Development</h4>
          <ul>
            <li>iOS, Android</li>
            <li>React, VueJS</li>
            <li>Python, Java, PHP</li>
          </ul>
        </div>
      </div>
      <div class="column is-one-third">
        <div class="box">
          <h4>Knowledge</h4>
          <ul>
            <li>Blockchain</li>
            <li>Artificial Intelligence</li>
            <li>Bioinformatics</li>
          </ul>
        </div>
      </div>
    </div>
  </section>
  </div>
</template>

<script>
import FrontHeader from '@/components/FrontHeader'
import Posts from '@/components/Posts'

export default {
  components: {
    FrontHeader,
    Posts
  }
}
</script>

<style lang="scss">
h4 {
  margin-bottom: 1rem;
  font-size: 1.25rem;
  font-family: "Kanit", sans-serif;
  text-transform: uppercase;
  letter-spacing: 0.075rem;
}
</style>
