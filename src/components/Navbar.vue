<template>
  <div>
  <b-navbar toggleable="lg" type="dark" variant="dark">
    <b-navbar-brand href="#" class="margen1">
      <b-icon icon="justify"></b-icon>
      My App
    </b-navbar-brand>
    <!-- <b-navbar-toggle target="nav-collapse"></b-navbar-toggle> -->
    <b-navbar-nav style="margin-left:auto">
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">INICIO</b-nav-item>
          <b-nav-item href="#">BUSCAR</b-nav-item>
          <b-nav-item href="#">ACERCA DE</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar-nav>

  </b-navbar>
</div>
    
  </template>


  <style scoped>
 .margen1{
    padding-left: 1rem;
  }
  </style>