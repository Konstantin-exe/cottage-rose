<template>
  <div class="home">
    <img
      alt="rosen hintergrund"
      src="../assets/bg-roses.jpeg"
      id="background-img"
    />
    <b-container class="description-container">
      <b-row class="justify-content-md-center">
        <div>
          <h1>Melitta Müllner</h1>
          <h6>Geschäftsführerin</h6>
          <img
            alt="Bild der Geschäftsführerin Melitta Müllner"
            src="../assets/melitta.jpeg"
            id="portrait"
          />
          <b-row class="justify-content-sm-center">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis, eos
            veniam dolorem, natus numquam itaque facere molestias voluptatum ex
            minima voluptas reprehenderit facilis voluptatibus aliquam sapiente
            vitae quod. Molestias, maxime. Lorem ipsum dolor sit amet
            consectetur adipisicing elit. Eum possimus iste veritatis
            necessitatibus illum et rem fugit suscipit in! Ab culpa porro, error
            assumenda sequi odio illo soluta quod et.</b-row
          >
        </div>
      </b-row>
    </b-container>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
};
</script>

<style scoped>
img h1 {
  margin-top: 500px;
}
#background-img {
  display: flex;
  object-fit: cover;
  height: 100vh;
  width: 100%;
  z-index: -1;
  margin-bottom: 50px;
}
span {
  display: block;
  justify-content: center;
  width: 80%;
}
#portrait {
  width: 25%;
  border-radius: 50%;
  margin: 20px;
}
</style>
