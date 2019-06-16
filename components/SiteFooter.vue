<template>
  <footer class="container">
    <div class="columns">
      <div class="column is-one-third">
        <div class="subtitle">
          Don't be shy
        </div>
        <div class="title">
          Come say hi
        </div>
      </div>
      <div class="column is-one-third">
        </div>
      <div class="column is-one-third">
        <address>
          Kanaalpark 157<br>
          2321 JW Leiden
        </address>
        <div class="phone">
          Tel: <a href="tel:+31622813087">+31 (0) 6 - 22 81 30 87</a>
        </div>
        <div class="email">
          Email: <a href="mailto:info@wearebrave.agency">info@wearebrave.agency</a>
        </div>
      </div>
    </div>
    <hr />
    <div class="copyright">
      &copy; 2019 Brave
    </div>
  </footer>
</template>

<style lang="sass" scoped>
@import "../node_modules/bulma/sass/utilities/mixins"

footer
  padding-left: 1.5rem
  padding-right: 1.5rem
  margin-top: 3rem
  text-align: center

  +desktop
    text-align: left

.title
  +desktop
    font-size: 2.5rem

address
  margin-bottom: 1rem

.copyright
  padding-bottom: 1rem
</style>
