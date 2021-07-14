<template>
  <div class="container">
    <div>
    <form
action="https://formspree.io/f/xknkvboz"
method="POST"
>
<label>
  Your email:
  <input type="email" name="_replyto">
</label>
<label>
  Your message:
  <textarea name="message"></textarea>
</label>

<!-- your other form fields go here -->

<button type="submit">Send</button>
</form>
      <h1 class="title">
        The Life Saving Station
      </h1>
      <h2 class="subtitle">
        Videos and Tracts
      </h2>

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
