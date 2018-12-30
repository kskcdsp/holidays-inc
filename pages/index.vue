<template>
  <section class="container is-center">
    <div class="index-wrap">
      <img src="~/assets/logo.png">
      <h1 class="title has-text-purple">
        Holidays Inc.
      </h1>
      <h2 class="subtitle subtitle-position">
        Arthur's Portfolio
      </h2>
      <div class="column">
        <div class="card">
          <header class="card-header">
            <p class="card-header-title">
              Check My Portfolio
            </p>
          </header>
          <div class="card-content">
            <div class="content japanese-font-family">
              アーサー@外資系企業の中の人です。
              <br>
              ポートフォリオを作りました。
              <br>
              良かったら見てみてください。
            </div>
          </div>
          <footer class="card-footer">
            <a
              href="/profile"
              class="card-footer-item has-text-purple">Profile</a>
            <a
              href="/contact"
              class="card-footer-item has-text-purple">Contact</a>
          </footer>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  min-height: 80vh;
  display: flex;
  justify-content: center;
  font-family: 'Skia-Regular_Black';
}

.index-wrap {
  position: relative;
  top: 7rem;
}

.title {
  display: block;
  font-weight: 300;
  font-size: 60px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.card {
  box-shadow: 0 2px 3px #5861d3, 0 0 0 1px #5861d3;
}

.card-header {
  box-shadow: 0 1px 2px #5861d3;
}

.card-footer {
  border-top: 1px solid #5861d3;
}

.card-footer-item:not(:last-child) {
  border-right: 1px solid #5861d3;
}

.card-header-title {
  position: relative;
  left: 25%;
}

.japanese-font-family {
  font-family: 'ヒラギノ角ゴ StdN', 'Hiragino Kaku Gothic StdN', sans-serif;
}

.is-center {
  text-align: center !important;
}

.has-text-purple {
  color: #5861d3;
}
</style>
