<template>
    <b-container>
  <b-navbar toggleable="lg" type="light" fixed="top" class="dogs" light>
    <b-navbar-brand href="#">Vetcare</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#start">Start</b-nav-item>
        <b-nav-item href="#services">Services</b-nav-item>
        <b-nav-item href="#about">About</b-nav-item>
        <b-nav-item href="#price">Price</b-nav-item>
        <b-nav-item href="#footer">Contact</b-nav-item>
        
      </b-navbar-nav>
      <b-navbar-nav right class="ml-auto">
        <a href="">+7-111-222-33-44</a>
      </b-navbar-nav>

    </b-collapse>
  </b-navbar>
 
    </b-container>

</template>

<style lang="scss">
.dogs {
  font-size: 2rem;
}

</style>