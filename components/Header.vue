<template>
  <section class="hero is-medium header-bg-color">
    <div class="hero-head">
      <nav class="navbar">
        <div class="container">
          <div class="navbar-brand">
            <nuxt-link
              to="/"
              class="navbar-item has-text-white">
              <font size="5"><b class="holidays-font">Holidays Inc.</b></font>
            </nuxt-link>
          </div>
          <div
            id="navbarMenuHeroA"
            class="navbar-menu">
            <div class="navbar-end">
              <nuxt-link
                to="/profile"
                class="navbar-item">
                <font size="4"><b class="button is-outlined is-white has-text-white header-button-font">Profile</b></font>
              </nuxt-link>
              <nuxt-link
                to="/contact"
                class="navbar-item has-text-white header-button-font">
                <font size="4"><b class="button is-outlined is-white">Contact</b></font>
              </nuxt-link>
            </div>
          </div>
        </div>
      </nav>
    </div>
  </section>
</template>

<style>
.header-bg-color {
  background-color: #5861d3;
}

.holidays-font,
.header-button-font {
  font-family: 'Skia-Regular_Black';
}
</style>
