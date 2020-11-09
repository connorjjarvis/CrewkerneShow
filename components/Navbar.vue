<template>
<b-container fluid="md" class="text-center">
  <b-navbar toggleable="lg" type="dark">
    <b-navbar-brand href="#"><h1>Crewkerne Show</h1></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="/">Home</b-nav-item>
        <b-nav-item href="/schedule">Schedule & Entry</b-nav-item>
        <b-nav-item href="/rules">Rules</b-nav-item>
        <b-nav-item href="/photos">Photos</b-nav-item>
        <b-nav-item href="/contact">Contact us</b-nav-item>
      </b-navbar-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="https://www.lionsclubs.org/en"><img src="../assets/lions.webp" /></b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</b-container>
</template>

<script lang="ts">
export default {
    name: 'Navbar',
    computed: {},
    methods: {}
};
</script>

<style>
h1 {
  color: #41935a;
  text-shadow: 2px 2px 0px #1a3823, 5px 4px 0px rgba(0,0,0,0.15);
}
.navbar-dark .navbar-nav .nav-link {
  font-size: 1.1rem; 
  color: #ffffff;
  text-shadow: 2px 2px 0px #1a3823, 5px 4px 0px rgba(0,0,0,0.15) ;
}

.navbar-dark .navbar-nav .nav-link:hover { 
  color: #41935a;
}


</style>