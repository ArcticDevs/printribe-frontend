<template>
  <div>
    <div id="nav">
      <div>
        <b-navbar toggleable="lg" type="dark" class="navbar">
          <img src="/img/Printibe-logo1.png" class="Logo" />

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <!-- Right aligned nav items -->

            <b-navbar-nav class="ml-auto">
              <!-- <b-nav-item href="#">Sign Up</b-nav-item>
              <b-nav-item href="#">Sign In</b-nav-item> -->
              <b-nav-item href="#">
                <b-icon icon="search" aria-hidden="false"> </b-icon
              ></b-nav-item>
              <b-nav-item href="#">Dropship Terms</b-nav-item>
              <b-nav-item href="#">Cart</b-nav-item>
              <b-nav-item href="#">Contact Us</b-nav-item>
              <b-nav-item-dropdown right>
                <!-- Using 'button-content' slot -->
                <template #button-content>
                  <li class="text-white">User</li>
                </template>
                <b-dropdown-item href="#">Sign In</b-dropdown-item>
                <b-dropdown-item href="#">Sign Up</b-dropdown-item>
              </b-nav-item-dropdown>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar {
  background-color: #231f20;
  /* height: 80px; */
  z-index:999;
}

.Logo {
  height: 35px;
}

.nav-link {
  color: #fff !important;
  margin: 0 10px 0 10px;
}

@media(max-width:992px){
  .navbar-collapse{
  background-color: #231F20;
  margin-top:30px;
  position:fixed;
  left:0;
  width:100%;
  top:20px;
  padding:20px;
}
}


h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
  font-size: 20px;

}

.navbar-nav .nav-link:hover,
.navbar-nav .nav-link:focus,
.navbar-nav .nav-link:active,
.navbar-nav .nav-link:after
 {
  outline: 0;
  border:none;
}
</style>
