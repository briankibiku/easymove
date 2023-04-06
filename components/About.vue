<template>
  <b-container fluid>
    <b-row align-v="center" fluid="md" style="margin: 1em;">
      <b-col sm="6">
          <b-img src="../assets/moving.png" fluid alt="Responsive image"></b-img>
      </b-col>
      <b-col sm="6" class="animate__animated animate__backInRight">
          <h3 class="title"><span style="color: #1C3583;">EasyMove,</span><span style="color: #E6007E;"> the moving experts!</span></h3>
          <h4>Make your next move with us</h4>
          <!-- <button class="btn">Get in touch</button> -->
          <a class="btn" href="/move">Get in touch</a>
      </b-col>
  </b-row>
</b-container>
</template>

<script>
export default {
  head: {
    title: "Home",
    link: [
      {
        rel: "stylesheet",
        href: "https://fonts.googleapis.com/css?family=Work Sans",
      },
    ],
  },
};
</script>
<style>
.title {
  color: #000;
  font-weight: bolder;
  font-size: 3em;
}
.btn {
  background-color: #E6007E;
  color: #fff;
}
</style>
