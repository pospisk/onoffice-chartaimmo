<template>
  <div id="app">
    <Header />
      <div class="container">
        <div class="row">
          <div class="col-6">
            <h1>Heading</h1>
          </div>
          <div class="col-6">
            <h1>Heading</h1>
          </div>
        </div>
      </div>
    <Footer />
  </div>
</template>

<script>
import Header from './components/layout/Header.vue'
import Footer from './components/layout/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
}
</script>
