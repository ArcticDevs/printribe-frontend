<template>
  <!-- Site footer -->
  <footer class="site-footer">
    <div class="container-fluid">
      <div class="row">
        <div class="col-sm-12 col-md-5">
          <img src="/img/Printibe-logo1.png" class="FooterLogo" />
          <p class="text-left">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>

          <ul class="social-icons mx-auto">
            <li>
              <a class="facebook" href="#">
                <b-icon icon="facebook" aria-hidden="false" scale="1.5"></b-icon
              ></a>
            </li>
            <li>
              <a class="twitter" href="#">
                <b-icon icon="twitter" aria-hidden="false" scale="1.5"></b-icon
              ></a>
            </li>
            <li>
              <a class="twitter" href="#">
                <b-icon icon="telephone" aria-hidden="false" scale="1.5"></b-icon
              ></a>
            </li>
            <li>
              <a class="dribbble" href="#"
                ><b-icon
                  icon="instagram"
                  aria-hidden="false"
                  scale="1.5"
                ></b-icon
              ></a>
            </li>
            <li></li>
          </ul>
        </div>
        <div class="col-xs-6 col-md-2 ml-sm-5">
          <h6>ABOUT</h6>
          <ul class="footer-links">
            <li>History</li>
            <li>Our Team</li>
            <li>Brand Guideliness</li>
            <li>Terms & Condition</li>
            <li>Privacy Policy</li>
          </ul>
        </div>
        <div class="col-xs-6 col-md-2">
          <h6>SERVICES</h6>
          <ul class="footer-links">
            <li>How to Order</li>
            <li>Our Product</li>
            <li>Order Status</li>
            <li>Promo</li>
            <li>Payment Methods</li>
          </ul>
        </div>
        <div class="col-xs-6 col-md-2">
          <h6>OTHER</h6>
          <ul class="footer-links">
            <li>About Us</li>
            <li>Help</li>

            <li>Privacy</li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.FooterLogo{
    max-width: 80%;
    height:40px;
    margin-bottom:10px;
}

h6{
  font-weight:bolder;
}

li{
  line-height:1.5rem;
  margin-bottom:5px;
}

.site-footer {
  background-color: #26272b;
  padding: 45px 0 20px;
  font-size: 15px;
  line-height: 24px;
  color: #dfdfdf;
}
.site-footer hr {
  border-top-color: #bbb;
  opacity: 0.5;
}
.site-footer hr.small {
  margin: 20px 0;
}
.site-footer h6 {
  color: #fff;
  font-size: 16px;
  text-transform: uppercase;
  margin-top: 5px;
  letter-spacing: 2px;
}
.site-footer a {
  color: #737373;
}
.site-footer a:hover {
  color: #3366cc;
  text-decoration: none;
}
.footer-links {
  padding-left: 0;
  list-style: none;
}
.footer-links li {
  display: block;
}
.footer-links a {
  color: #737373;
}
.footer-links a:active,
.footer-links a:focus,
.footer-links a:hover {
  color: #3366cc;
  text-decoration: none;
}
.footer-links.inline li {
  display: inline-block;
}
.site-footer .social-icons {
  text-align: left;
}
.site-footer .social-icons a {
  width: 40px;
  height: 40px;
  line-height: 40px;
  margin-left: 6px;
  margin-right: 0;
  border-radius: 100%;
  background-color: #33353d;
}
.copyright-text {
  margin: 0;
}
@media (max-width: 991px) {
  .site-footer [class^="col-"] {
    margin-bottom: 30px;
  }
}
@media (max-width: 767px) {
  .site-footer {
    padding-bottom: 0;
  }
  .site-footer .copyright-text,
  .site-footer .social-icons {
    text-align: center;
  }
}
.social-icons {
  padding-left: 0;
  margin-bottom: 0;
  list-style: none;
}
.social-icons li {
  display: inline-block;
  margin-bottom: 4px;
}
.social-icons li.title {
  margin-right: 15px;
  text-transform: uppercase;
  color: #96a2b2;
  font-weight: 700;
  font-size: 13px;
}
.social-icons a {
  background-color: #eceeef;
  color: #818a91;
  font-size: 16px;
  display: inline-block;
  line-height: 44px;
  width: 44px;
  height: 44px;
  text-align: center;
  margin-right: 8px;
  border-radius: 100%;
  -webkit-transition: all 0.2s linear;
  -o-transition: all 0.2s linear;
  transition: all 0.2s linear;
}
.social-icons a:active,
.social-icons a:focus,
.social-icons a:hover {
  color: #fff;
  background-color: #29aafe;
}
.social-icons.size-sm a {
  line-height: 34px;
  height: 34px;
  width: 34px;
  font-size: 14px;
}
.social-icons a.facebook:hover {
  background-color: #3b5998;
}
.social-icons a.twitter:hover {
  background-color: #00aced;
}
.social-icons a.linkedin:hover {
  background-color: #007bb6;
}
.social-icons a.dribbble:hover {
  background-color: #ea4c89;
}
@media (max-width: 767px) {
  .social-icons li.title {
    display: block;
    margin-right: 0;
    font-weight: 600;
  }
}
</style>
