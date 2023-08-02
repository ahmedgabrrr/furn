<template>
  <div fixed="top" class="navBar">
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand class="logo navbar-brand py-0 pl-5" href="#"
        ><img
          src="https://www.zarla.com/images/zarla-furniture-fixture-1x1-2400x2400-20210701-cqdf6qdygchtg3jmb4yx.png?crop=1:1,smart&width=250&dpr=2"
          alt=""
      /></b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item pl-5 href="#">Home</b-nav-item>
          <b-nav-item href="#">Products</b-nav-item>
          <b-nav-item href="#">Contact Us</b-nav-item>
        </b-navbar-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-form-input
              size="sm"
              class="mr-sm-2"
              placeholder="Search"
            ></b-form-input>
          </b-nav-form>
        </b-navbar-nav>
        <b-navbar-nav>
          <b-nav-item href="#" class="sign-in">Sign In</b-nav-item>
          <b-nav-item class="shop"
            ><img
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQcB1dmICjiwVjueUrnXw82dYUVnR5k_0-KK18zDYg&s"
              alt=""
          /></b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
<script>
</script>
<style scoped>
.navBar {
  width: 100%;
  border-bottom: 1px solid #dcdcdc;
}
.bg-info {
  background-color: #f8f8f8 !important;
}
.nav-link {
  color: #000;
  font-size: 17px;
}
.logo {
  padding-left: 3rem !important;
}
.logo img {
  vertical-align: middle;
  width: 50px;
  height: 50px;
}
.sign-in a {
  position: absolute;
  right: 45px;
  top: 25%;
}
.shop img {
  width: 40px;
  position: absolute;
  right: 125px;
  top: 15px;
}
</style>