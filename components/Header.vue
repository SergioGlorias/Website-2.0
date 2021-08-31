<template>
  <div>
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
            
        </b-collapse>
      </b-container>
    </b-navbar>
  </div>
</template>

<script>
export default {}
</script>

<style>
.navbar-brand {
  font-family: 'Lobster', cursive;
  font-size: 35px;
}
.bg-especial {
  background: linear-gradient(0.25turn, #4a06a3, #880707);
}
</style>