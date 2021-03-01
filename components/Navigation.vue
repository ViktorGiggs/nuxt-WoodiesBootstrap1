<template>
  <nav class="navbar navbar-expand-md navbar-light">
    <div class="container-fluid ">
      <a href="#" class="navbar-brand"><img src="~/assets/pictures/Group28.png" class="navbar-brand-img" alt="logo"></a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse text-end bar-link flex-row-reverse " id="navbarResponsive">
        <ul class="navbar-nav ">
          <li class="nav-item active pr-5">
            <nuxt-link to="/" class="nav-link">Home</nuxt-link>
          </li>
          <li class="nav-item pr-5">
            <a href="#" class="nav-link">About US</a>
          </li>
          <li class="nav-item pr-5">
            <a href="#" class="nav-link">How it works</a>
          </li>
          <li class="nav-item pr-5">
            <nuxt-link to="/categories" class="nav-link">Categories</nuxt-link>
          </li>
          <li class="nav-item pr-5">
            <a href="#" class="nav-link">Testimony</a>
          </li>
          <li class="nav-item pr-5">
            <button type="button" class="btn btn-outline-secondary">SIGN UP</button>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
name: "Navigation"
}
</script>

<style scoped>

</style>
