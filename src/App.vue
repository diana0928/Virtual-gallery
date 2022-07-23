<template>
  <div id="app">
    <Header></Header>
    <!-- <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
     -->
     <fade-transition>
      <router-view/>
    </fade-transition>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
import {FadeTransition} from 'vue2-transitions'
export default {
  components: {
    Header,
    FadeTransition,
    Footer
}
}
</script>