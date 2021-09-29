<template>
  <div class="">
    <!-- <h1 class="text-center">Title</h1> -->
    <div class="row w-100 m-0">
      <div class="col-12 col-md-6 py-5 bgBlue">
        <h1 class="mb-3">How does it work?</h1>
        <ul class="text-light">
          <li>
            Register yourself/ your business with us! Open a free Printribe
            account - (hyperlink)
          </li>
          <li>Choose what you want to sell & design it using Printribe tool</li>
          <li>Have a mockup of all your curated products on your account</li>
          <li>Place a sample order to test & verify the product</li>
          <li>Promote & exhibit it at your store</li>
          <li>Keep a track of your sales on the merchant account</li>
        </ul>
        <div class="w-100 text-center">
          <div class="readMoreBtn mx-auto">MORE ABOUT PROCESS</div>
        </div>
      </div>
      <div class="col-12 col-md-6 p-0 bg-white">
        <img
          src="/img/three-color-gears.gif"
          alt=""
          class="img-responsive image"
        />
      </div>
    </div>
  </div>
</template>


<style scoped>
h1 {
  font-weight: bolder;
  font-size: 3.4.5vmax;
  color: #fff;
  text-align: center;
}

ul {
  list-style: none;
}

li {
  line-height: 2rem;
  font-size: 1.2rem;
  margin-bottom: 10px;
}

li:before {
  content: "\2713";
  display: inline-block;
  color: rgb(255, 184, 91);
  padding: 0 10px 0 0;
  font-weight: bolder;
}

.image {
  max-width: 100%;
  height: 100%;
  object-fit: cover;
}

.bgBlue {
  background-color: #29649d;
  background-image: url(/img/dotsPattern.png);
  background-repeat: no-repeat;
}

.readMoreBtn {
  background-color: #231f20;
  color: #fff;
  width: 20rem;
  max-width: 100%;
  padding: 15px;
  font-size: 1.2rem;
  margin-top: 30px;
  filter: drop-shadow(0 2px 5px rgb(107, 107, 107));
  border-radius: 10px;
}
.readMoreBtn:hover {
  color: rgb(228, 226, 226);
  cursor: pointer;
}

@media (max-width: 768px) {
  li {
    font-size: 1rem;
  }
  .readMoreBtn {
    font-size: 1rem;
  }
}
</style>
