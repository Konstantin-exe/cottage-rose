<template>
  <div class="home">
    <img
      alt="rosen hintergrund"
      src="../assets/bg-roses.jpeg"
      id="background-img"
    />
    <div>
      <h1>Melitta Müllner</h1>
      <img
        alt="Bild der Geschäftsführerin Melitta Müllner"
        src="../assets/melitta.jpeg"
        id="portrait"
      />
      <span
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis, eos
        veniam dolorem, natus numquam itaque facere molestias voluptatum ex
        minima voluptas reprehenderit facilis voluptatibus aliquam sapiente
        vitae quod. Molestias, maxime.</span
      >
    </div>
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
}
span {
  display: block;
  justify-content: center;
  width: 80%;
}
#portrait {
  width: 25%;
}
</style>
