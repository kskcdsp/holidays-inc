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
              <img src="~/assets/pen-header-logo.png">
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
                  <nuxt-link
                    to="/contact"
                    class="header-button-font">
                    <font size="3"><b class="button has-text-white is-purple">Contact</b></font>
                  </nuxt-link>
                  <a
                    href="http://organics-life.com"
                    class="header-button-font"
                    target="”_blank”">
                    <font size="3"><b class="button has-text-white is-purple">Blog</b></font>
                  </a>
                  <a
                    class="button is-purple"
                    href="https://twitter.com/arthur_foreign"
                    target="”_blank”">
                    <span class="icon">
                      <i class="fab fa-twitter has-text-white"/>
                    </span>
                    <span class="has-text-white holidays-font">Twitter</span>
                  </a>

                  <a
                    class="button is-purple"
                    href="https://github.com/kskcdsp"
                    target="”_blank”">
                    <span class="icon">
                      <i class="fab fa-github has-text-white"/>
                    </span>
                    <span class="has-text-white holidays-font">GitHub</span>
                  </a>
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

.button {
  margin-right: 0.5rem;
}
</style>
