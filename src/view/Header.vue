<template>
  <div>
    <div class="header">
      <ul class="navigation-menu">
        <li class="navigation-brand navigation-item">
          <a href="#">
            <img src="../assets/logo-ht-icon.png" alt="" class="navigation-logo">
            <img src="../assets/logo-ht-text.png" alt="" class="navigation-logo-text">
          </a>
        </li>
        <li class="navigation-item">
          <a href="#" class="navigation-link">Trades</a>
        </li>
        <li class="navigation-item">
          <a href="#" class="navigation-link">Cost Guides</a>
        </li>
        <li class="navigation-item">
          <a href="#" class="navigation-link">Blogs</a>
        </li>
      </ul>
      <ul class="navigation-menu">
        <li class="navigation-item">
          <a href="#" class="navigation-link">Get Quotes</a>
        </li>
        <li class="navigation-item">
          <button class="btn btn-purple">Register Business</button>
        </li>
        <li class="navigation-item">
          <a href="#" class="navigation-link">Login</a>
        </li>
      </ul>
      <i class='bx bx-menu mobile tab mobile-menu'></i>
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.header {
  width: 100%;
  height: 4rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: fixed;
  z-index: 999;
  border-bottom: 1px solid #dfe3e7;
  background-color: #fff;
}
.navigation-menu {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
  gap: 20px;
  align-items: center;
}

.navigation-menu li:last-child {
  padding-right: 10px;
}

.navigation-item {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
}

.navigation-link {
  color: #666;
  text-decoration: none;
  font-weight: 800;
}

.navigation-link:hover {
  color: #7367f0;
}

.navigation-brand a {
  display: flex;
  align-items: center;
  gap: 15px;
}

.mobile {
  display: none;
}

.tab {
  display: none;
}

.mobile-menu {
  font-size: 2rem;
  padding-right: 10px;
}

/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  .desktop {
    display: none;
  }
  .navigation-item:not(.navigation-brand) {
    display: none;
  }
  .mobile {
    display: block;
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
  .navigation-item:not(.navigation-brand) {
    display: none;
  }
  .mobile {
    display: block;
  }
}



/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (max-width: 992px) {
  .tab {
    display: block;
  }
  .desktop {
    display: none;
  }
  .navigation-item:not(.navigation-brand) {
    display: none;
  }
  .mobile {
    display: block;
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