<template>
  <div class="container-fluid">
    <div class="container">
      <h1>TITLE</h1>
      <p class="subHeading">
        Lorem ipsum dolor sit amet, consecetur adipiscing elit . Vicamus lacinia
        odio vitea vestibulum vestibulum
      </p>
      <div class="row text-white">
        <div class="col-md-4 col-sm-12">
          <h1>1200+</h1>
          <p>Text</p>
        </div>
        <div class="col-md-4 col-sm-12 ">
          <h1>2000+</h1>
          <p>Active Menber</p>
        </div>
        <div class="col-md-4 col-sm-12">
          <h1>100+</h1>
          <p>Community</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.row p{
    font-size: 22px;
    font-weight: 300;
    text-align: center;
}
.row{
    margin-top:100px
}
h1 {
  font-weight: bolder;
  font-size: 60px;
  color: #fff;
}
.subHeading {
  color: #fff;
  font-size: 20px;
  margin-bottom: 50px;
  margin-top: 20px;
}
.container-fluid {
  background-color: #231f20;
}
.container{
   /* height: 600px; */
   padding-top: 100px;
   padding-bottom: 100px;
}
</style>
