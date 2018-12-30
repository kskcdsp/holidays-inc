<template>
  <section class="hero is-medium is-purple">
    <div class="hero-head">
      <nav
        class="navbar"
        role="navigation"
        aria-label="main navigation">
        <div
          id="navbarToggleMenu"
          class="container">
          <div class="navbar-brand">
            <nuxt-link
              to="/"
              class="navbar-item has-text-white">
              <font size="5"><b
                class="holidays-font">Holidays Inc.</b>
              </font>
            </nuxt-link>
            <a
              :class="{'is-active': isActive}"
              role="button"
              class="navbar-burger burger has-text-white"
              aria-label="menu"
              aria-expanded="false"
              data-target="navbarBasicExample"
              @click="openAndClose">
              <span aria-hidden="true"/>
              <span aria-hidden="true"/>
              <span aria-hidden="true"/>
            </a>
          </div>

          <div
            id="navbarBasicExample"
            :class="{'is-active': isActive}"
            class="navbar-menu">
            <div class="navbar-start"/>
            <div class="navbar-end">
              <div class="navbar-item">
                <div class="buttons">
                  <nuxt-link
                    to="/profile">
                    <font size="3"><b class="button has-text-white is-purple header-button-font">Profile</b></font>
                  </nuxt-link>
                  <div>
                    &nbsp;
                  </div>
                  <nuxt-link
                    to="/contact"
                    class="header-button-font">
                    <font size="3"><b class="button has-text-white is-purple">Contact</b></font>
                  </nuxt-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </nav>
    </div>
  </section>
</template>
<script>
import Vue from 'vue'
export default {
  el: 'navbarToggleMenu',
  data: function() {
    return {
      isActive: false
    }
  },
  methods: {
    openAndClose: function() {
      this.isActive = !this.isActive
    }
  }
}
</script>

<style>
.is-purple {
  background-color: #5861d3;
}

.holidays-font,
.header-button-font {
  font-family: 'Skia-Regular_Black';
}
</style>
