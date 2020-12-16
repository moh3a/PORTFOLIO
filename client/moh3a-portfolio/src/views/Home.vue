<template>
  <div id="home">
    <About/>
    <Contact/>
  </div>
</template>

<script>
// @ is an alias to /src
import About from "@/components/About"
import Contact from "@/components/Contact"

export default {
  name: 'Home',
  components: {
    About,
    Contact
  }
}
</script>

<style>
  #nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>