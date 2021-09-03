<template>
  <div>
    <Header style="z-index: 7" />
    <div>
      <hr class="my-4" />
      <b-container fluid="lg" class="bg-light">
        <b-row class="d-flex bg-light pt-5">
          <b-col id="name" order="1" class="ml-2">
            <h3>
              Olá <br />
              Eu sou o Sérgio Glórias
            </h3>
          </b-col>
          <b-col id="img" order="2" class="ml-auto mr-3">
            <b-img
              src="~/assets/img/my-photo.jpg"
              rounded="photo"
              fluid
            ></b-img>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.rounded-photo {
  border-radius: 20px;
}

#name {
  max-width: 600px;
  position: fixed;
}

#name h3 {
  font-size: 110px;
  font-family: 'Shadows Into Light', cursive;
  font-weight: bold;
  color: royalblue;
  z-index: auto;
}

#img {
  max-width: 500px;
}
</style>
