<template>
  <section class="container is-center">
    <div class="index-wrap">
      <h1 class="title has-text-purple">
        Holidays Inc.
      </h1>
      <h2 class="subtitle index-subtitle-potision">
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
              アーサー@外資系企業の中の人。です。
              <br>
              <br>
              Nuxt.jsとVue.jsを使って、会社のPR & 自分のポートフォリオを作ってみました。
              <br>
              <br>
              <span class="has-text-purple">Holidays Inc.</span>は僕の会社の名前ですね。
              <br>
              <br>
              「<span class="has-text-purple">毎日が休日のように楽しい会社</span>」を目指したいなと思ったので、何となくそんな感じの名前になりました。(思考時間5秒)
              <br>
              <br>
              会社名から分かるように「起業！」「成長！」「増収増益！」とか鼻息荒く開業してません。
              <br>
              <br>
              ただの趣味 & 節税です。
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
  top: 5rem;
}

.title {
  display: block;
  font-weight: 300;
  font-size: 50px;
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
  width: 22rem;
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

.box:not(:last-child),
.content:not(:last-child),
.notification:not(:last-child),
.progress:not(:last-child),
.table:not(:last-child),
.table-container:not(:last-child),
.title:not(:last-child),
.subtitle:not(:last-child),
.block:not(:last-child),
.highlight:not(:last-child),
.breadcrumb:not(:last-child),
.level:not(:last-child),
.list:not(:last-child),
.message:not(:last-child),
.tabs:not(:last-child) {
  margin-bottom: 0px;
}

.index-subtitle-potision {
  position: relative;
  top: 1rem;
}

.card-content {
  text-align: left !important;
}
</style>
