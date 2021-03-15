<template>
  <div>
    <div class="footer">
      <div class="content">
        <div class="website-brand footer-item">
          <div class="footer-item-title">
            <a href="">
              <img src="../assets/logo-ht-icon.png" alt="" class="navigation-logo">
              <img src="../assets/logo-ht-text.png" alt="" class="navigation-logo-text">
            </a>
          </div>
          <hr>
          <div class="slogan">
            <h4>Australia's most trusted trades provider</h4>
          </div>
        </div>
        <div class="footer-item">
          <div class="footer-item-title">
            <h5>Customers</h5>
          </div>
          <hr>
          <ul class="footer-item-body">
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
          </ul>
        </div>
        <div class="footer-item">
          <div class="footer-item-title">
            <h5>Tradies</h5>
          </div>
          <hr>
          <ul class="footer-item-body">
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
          </ul>
        </div>
        <div class="footer-item">
          <div class="footer-item-title">
            <h5>HIREtrades</h5>
          </div>
          <hr>
          <ul class="footer-item-body">
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
            <li><a href="">Get Quotes</a></li>
          </ul>
        </div>
        <div class="footer-item">
          <div>
            <div class="footer-item-title">
              <h5>Download our apps</h5>
            </div>
            <hr>
            <div class="footer-item-body">
              <div class="logo-container">
                <img src="../assets/ios-black.png" alt="">
                <img src="../assets/android-black.png" alt="">
              </div>
            </div>
          </div>
          <div class="follow-us">
            <div class="footer-item-title">
              <h5>Follow us</h5>
            </div>
            <hr>
            <ul class="footer-item-body footer-item-social">
              <li><a href=""><i class="bx bxl-facebook"></i></a></li>
              <li><a href=""><i class="bx bxl-twitter"></i></a></li>
              <li><a href=""><i class="bx bxl-instagram"></i></a></li>
              <li><a href=""><i class="bx bxl-pinterest"></i></a></li>
              <li><a href=""><i class="bx bxl-linked"></i></a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-additional">
      <div class="content">
        <div class="copyright">
          <span>© 2020 - www.HIREtrades.com.au | All Rights Reserved</span>
        </div>
        <div class="misc">
          <ul>
            <li><a href="">Privacy Policy</a></li>
            <div class="divider"></div>
            <li><a href="">Sitemap</a></li>
            <div class="divider"></div>
            <li><a href="">v_2.0.78</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.content {
  margin: 0 auto;
  width: 70%
}
.footer{
  background-color: #e6eaee;
}

.footer .content {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  padding: 1rem 2.2rem;
  gap: 10px;
  background-color: #e6eaee;
}

.footer-item li:not(:last-child) {
  margin-bottom: 10px;
}

.footer-item .footer-item-title{
  font-size: 1rem;
}

.footer-item .slogan{
  font-size: 1.2rem;
}

.footer-item-title a {
  display: flex;
  align-items: center;
  gap: 15px;
}

.footer-item-title h5 {
  font-size: 1.2rem;
}

.footer-item-social {
  display: flex;
  gap: 10px;
  font-size: 1rem;
}

.footer-additional {
  background-color: #e6eaee;
}

.footer-additional .content {
  display: flex;
  justify-content: space-between;
  font-size: 12px;
}

.logo-container {
  display: flex;
  gap: 20px;
}

.follow-us {
  margin-top: 50px;
}

.misc ul {
  display: flex;
  gap: 10px;
}
.misc ul li {
  border-right: 1px solid #dfe3e7;
}

.footer hr {
  margin-left: 0;
  width: 25%;
}

.divider {
  border-left: 1px solid #727e8c;
  margin-top: 2px;
  margin-bottom: 2px;
  vertical-align: middle;
}


/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  .desktop {
    display: none;
  }
  .mobile {
    display: block;
  }
  .footer .content {
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 40px;
  }

  .footer-additional .content {
    display: block;
    text-align: center;
  }

  .misc ul {
    justify-content: center;
  }


}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (max-width: 768px) {
  .tab {
    display: block;
  }
  .desktop {
    display: none;
  }

  .footer .content {
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 40px;
  }

  .footer-additional .content {
    display: block;
    text-align: center;
  }

  .misc ul {
    justify-content: center;
  }

}



/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (max-width: 992px) {
  .footer .content {
    grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
    gap: 40px;
  }

  .footer-additional .content {
    display: block;
    text-align: center;
  }

  .misc ul {
    justify-content: center;
  }
  
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
  .desktop {
    display: block;
  }
  .tab {
    display: none;
  }
  .mobile {
    display: none;
  }
}
</style>