<template>
  <div class="container">
    <div>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/gRg8JHYhQK8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <h1 class="title">
        The Life Saving Station
      </h1>
      <h2 class="subtitle">
        Videos and Tracts
      </h2>
      <div class="links">
        <a
          href="url"
          target="_blank"
          rel="noopener"
          class="button--green"
        >
          Contact
        </a>
        <a
          href="contact.vue"
          target="_blank"
          rel="noopener"
          class="button--grey"
        >
          About
        </a>
      </div>
    </div>
  </div>
</template>



<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
