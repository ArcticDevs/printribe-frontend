<template>
  <div class="CustomContainer">
    <div class="container"></div>
    <p class="subHeading">
      Lorem ipsum dolor sit amet, consecetur adipiscing elit . Vicamus lacinia
      odio vitea vestibulum vestibulum
    </p>
    <h1 class="text-center">TITLE</h1>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
h1 {
  font-weight: bolder;
  font-size: 3rem;
  color: #fff;
  margin-bottom: 30px;
}
.container {
  padding-top: 20vh;
  padding-bottom: 20vh;
    
}
.subHeading {
  color: #fff;
  font-size: 2rem;
  margin-bottom: 50px;
  margin-top: 20px;
  display: inline-block;
  vertical-align: middle;
  filter: brightness(1) !important;
}
.CustomContainer {
  height: 100vh;
  min-width: 100%;
  background-image: url("/4.jpg");
  filter: sepia(100%) hue-rotate(190deg) saturate(400%) brightness(.4);
  background-repeat: no-repeat;
  /* background-size:100% 100%; */
  background-size: cover;
}
@media (max-width:766px) {
    .container{
         padding-top: 10vh;
  padding-bottom: 10vh;
    }
    
}
@media (max-width:350px) {
    .container{
         padding-top: 5vh;

    }
    
}
</style>
