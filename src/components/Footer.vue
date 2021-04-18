<template>
  <b-container fluid="auto" class="footer-container">
    <b-row align-v="center" class="footer">
      <b-col>Hauptplatz 2, 7202 Bad Sauerbrunn </b-col>
      <a class="link" href="/impressum">Impressum</a>
      <b-col
        >tel: +43 676 / 455 84 15 <br />
        email: melitta.muellner@gmx.at
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: 'Footer',
};
</script>

<style>
.footer-container {
  margin-top: auto;

  background-color: #ea899a;
  color: white;
  margin-top: 50px;
}
.link {
  text-decoration: none;
  color: white;
}
</style>
