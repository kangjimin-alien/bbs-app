<template>
  <div id="app">
    <Header/>
    <visual/>
    <router-view/>
    <Gallery/>
    <Login/>
    <Footer/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import visual from "@/components/visual";
import Footer from "@/components/Footer";
export default {
  name: "App",
  components: {
    Header,
    visual,
    Footer
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>
