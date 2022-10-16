<template>
  <div>
    <div class="container">
      <header
        class="
          d-flex
          flex-wrap
          align-items-center
          justify-content-center justify-content-md-between
          py-3
        "
      >
        <nuxt-link
          to="/"
          class="
            d-flex
            align-items-center
            col-md-3
            mb-2 mb-md-0
            text-dark text-decoration-none
          "
        >
          <img src="/img/logo.webp" alt="Your Company" height="60"/>
        </nuxt-link>
        <GeneralNavbar />
        <div class="col-md-3 text-end">
          <nuxt-link class="btn btn-outline-primary me-2" to="/contact">
            Contact Us
          </nuxt-link>
          <button type="button" class="btn btn-primary">Download Theme</button>
        </div>
      </header>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>