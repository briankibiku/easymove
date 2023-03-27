<template>
  <b-container fluid>
    <b-row align-v="center" fluid="md" style="margin: 1em;">
      <b-col sm="6">
          <b-img src="../assets/trade.gif" fluid alt="Responsive image"></b-img>
      </b-col>
      <b-col sm="6">
          <h3 class="title animate__animated animate__backInRight">Welcome to Pro<span style="color: #FF0000;">Fx</span>, your <span style="color: #208600;">winning</span>  partner in <span style="color: #FF0000;">forex.</span></h3>
      </b-col>
  </b-row>
</b-container>
</template>

<script>
export default {
  head: {
    title: "About",
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
</style>
