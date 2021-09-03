<template>
  <div class="fix">
    <b-navbar toggleable="lg" type="dark" variant="especial">
      <b-container fluid="lg">
        <b-navbar-brand href="/">
          <img
            src="~/assets/img/tux.png"
            alt="Serginho"
            width="50"
            height="50"
            class="d-inline-block align-text-top rounded-circle"
          />
          <span class="my-auto">Serginho</span>
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse" />

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="ml-auto">
            <b-nav-item href="/"> <fa-icon icon="home"/> Principal</b-nav-item>
            <b-nav-item href="#"> <fa-icon icon="link"/> Link</b-nav-item>
            <b-nav-item href="#"> <fa-icon icon="link"/> Link</b-nav-item>
            <b-nav-item href="#"> <fa-icon icon="link"/> Link</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.navbar-brand {
  font-family: 'Lobster', cursive;
  font-size: 35px;
}
.bg-especial {
  background: linear-gradient(0.375turn, #4a06a3, #880707);
}
.fix {
    position: fixed;
    top: 0;
    width: 100%;
}
</style>