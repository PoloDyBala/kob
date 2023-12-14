<template>
  <div>
    <myNavBar />
    <router-view></router-view>
  </div>
</template>

<script>
import myNavBar from './components/NavBar.vue'
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap/dist/js/bootstrap"

export default {
  components: {
    myNavBar
  },
  setup() {
  }
}
</script>

<style>
body {
  background-image: url("@/assets/images/background.png");
  background-size: cover;
}
</style>
