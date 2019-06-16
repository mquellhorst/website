<template>
  <div class="column is-one-third">
    <div class="card">
      <span class="tag is-info">CASE</span>
      <div class="card-image">
        <figure class="image is-4by3">
          <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
        </figure>
      </div>
      <div class="card-content">
        <div class="content">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          Phasellus nec iaculis mauris.
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.card {
  position: relative;
  overflow: hidden;
}

.card-content {
  position: absolute;
  background-color: #fff;
  transition: transform 35ms ease;
}

.card:hover .card-content {
  transform: translateY(-100%);
}

.tag {
  position: absolute;
  top: 1rem;
  left: 1rem;
  z-index: 10;
}
</style>

