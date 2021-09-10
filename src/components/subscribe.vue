<template>
  <div class="container-fluid">
    <div class="container">
      <h1 class="text-center">SUBSCRIBE</h1>
      <p class="subHeading">
        Lorem ipsum dolor sit amet, consecetur adipiscing elit . Vicamus lacinia
        odio vitea vestibulum vestibulum
      </p>

      <div class="form-group">
        <form>
          <input
            type="text"
            name="useremail-id"
            id="useremail-id"
            placeholder="Enter your email"
          />
          <button type="submit" id="subscribe">
            Subscribe
          </button>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container-fluid {
  background-color: #231f20;
  background-image: url(/dotsPattern.png), url(/dotsPatternBottomRight.png);

  background-position: left top, right bottom;
  background-repeat: no-repeat;
}
h1 {
  font-weight: bolder;
  font-size: 3rem;
  color: #fff;
  margin-bottom: 30px;
}
.container {
  /* height: 600px; */
  padding-top: 100px;
  padding-bottom: 100px;
}
.subHeading {
  color: #fff;
  font-size: 1.5rem;
  margin-bottom: 50px;
  margin-top: 20px;
}

header {
  background: #0f0f6d;
  width: 100%;
  height: 100px;
}
header h1 {
  text-align: center;
  color: #fff;
  line-height: 100px;
  text-transform: uppercase;
  letter-spacing: 2px;
  font-weight: 700;
}

button {
  height: 65px;
  width: 100%;
  max-width: 445px;
  font-size: 16px;
  padding: 20px;
  line-height: 0;
  vertical-align: top;
  cursor: pointer;
  color: #fff;
  border: 0;
  border-radius: 0px 5px 5px 0px;
  background: #29649d;
}
button:hover {
  background: #29649d;
  box-shadow: 0 4px 10px hsl(34 100% 56% / 0.2);
}
form {
  display: flex;
}
input {
  min-width: 400px;
  height: 65px;
  width: 100%;
  border-radius: 5px 0 0 5px;
  background: #fff !important;
  padding: 16px;
  font-weight: normal;
  font-size: 18px;
  text-align: left;
  color: #000;
  opacity: 0.5;
}
.design-credits {
  margin: 20px 0;
  color: #ffffff;
}
.spacer {
  height: 50px;
}

@media screen and (max-width: 768px) {
  header h1 {
    font-size: 18px;
  }

  form {
    display: flex;
    flex-direction: column;
    width: 100%;
  }
  button {
    border-radius: 5px;
    max-width: 100%;
  }
  input {
    margin-bottom: 20px;
    min-width: 100%;
  }
  .card-title {
    font-size: 24px;
  }
  .card-sub-title {
    font-size: 18px;
  }
}
</style>
