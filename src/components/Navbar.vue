<template>
  <b-navbar toggleable type="dark" variant="dark">
    <b-navbar-brand href="#">
      <img class="logo__img d-inline-block align-top" src="../assets/ibrahim.png" alt="Ibrahim" />
    </b-navbar-brand>

    <b-navbar-toggle target="navbar-toggle-collapse">
      <template v-slot:default="{ expanded }">
        <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
        <b-icon v-else icon="chevron-bar-down"></b-icon>
      </template>
    </b-navbar-toggle>

    <b-collapse id="navbar-toggle-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#about">About</b-nav-item>
        <b-nav-item href="#project">Projects</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<style lang="scss" scoped>
.logo__img {
  height: 60px;
  width: 60px;
  filter: contrast(180%);
}
.navbar {
  background-color: #485563 !important;
  box-shadow: 1px 2px rgba(58, 40, 40, 0.2);
}
</style>
