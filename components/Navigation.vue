<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="container">
    <div class="navbar-brand">
      <nuxt-link to="/" class="navbar-item">
        BRAVE
      </nuxt-link>
    </div>

    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-end">
        <div class="navbar-item">
          <div class="buttons">
            <a class="button is-primary">
              <strong>Start a project</strong>
            </a>
          </div>
        </div>
      </div>
    </div></div>
  </nav>
</template>

<style lang="scss" scoped>
.navbar .container {
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}
.navbar-brand .navbar-item {
  padding-left: 0;
  font-size: 1.75rem;
  font-weight: 900;
  font-family: "Kanit", sans-serif;
}
.navbar-item {
  text-transform: uppercase;
  letter-spacing: 0.035rem;
  font-family: "Kanit", sans-serif;
}
</style>
