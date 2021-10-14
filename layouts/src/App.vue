<template>
<div id="app" >
  <Navbar />
  <Content />
  <Footer />
</div>
</template>

<script>
import Content from './components/Content.vue'
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Content,
    Navbar,
    Footer
  }
}
</script>

<style>

*,
*::before,
*::after {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

.container{
  max-width: 1280px;
  margin: 0 auto;
}

#app{
  min-height: 100vh;
  display: flex;
  flex-flow: column wrap;
}

</style>
