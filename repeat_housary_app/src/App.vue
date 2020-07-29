<template>
  <div id="app">
    <NavBar />
    <router-view />
  </div>
</template>

<script>

import NavBar from "@/components/global/NavBar"
// import "bootstrap";
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap/dist/js/bootstrap.min.js";

import "@fortawesome/fontawesome-free/css/all.min.css";
import "@fortawesome/fontawesome-free/js/all.js";

// import "@/assets/material.css";

import "bootstrap-select/dist/css/bootstrap-select.min.css";
import "bootstrap-select/dist/js/bootstrap-select.js";


export default {
  name: 'App',
  components:{
    NavBar
  }
}
</script>

<style>

* {
  margin: 0px;
}
#app {
  background: rgb(189, 212, 240);
  height: 1000px;
  text-align: right ;
}

</style>