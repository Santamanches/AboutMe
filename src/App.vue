<template>
  <div class="wrapper">
    <Navbar></Navbar>
    <Main></Main>
    <Footer></Footer>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'



export default {
  name: 'App',
  components: {
    Navbar,
    Main,
    Footer
  }
}
</script>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: arial;
}

a {
    text-decoration: none;
}
ul {
    list-style: none;
}
body {
  background: cadetblue;
}


</style>
