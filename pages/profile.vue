<template>
  <section class="container is-center">
    <div class="index-wrap">
      <h1 class="title has-text-purple">
        Holidays Inc.
      </h1>
      <h2 class="subtitle holidays-logo-position">
        Profile Page
      </h2>
      <article class="media">
        <figure class="media-left">
          <p class="image is-64x64">
            <img src="~/assets/1.png">
          </p>
        </figure>
        <div class="media-content">
          <div class="content">
            <p>
              <strong
                class="japanese-font-family"
                href="https://twitter.com/arthur_foreign"
                target="”_blank”">アーサー@外資系企業の中の人。</strong>
              <br>
              <small
                class="at-twitter-link"
                href="https://twitter.com/arthur_foreign"
                target="”_blank”">@arthur_foreign</small>
              <br>
              <span class="japanese-font-family">
                こんにちは！アーサー@外資系企業の中の人。
              </span>
            </p>
          </div>
          <nav class="level is-mobile">
            <div class="level-left">
              <a class="level-item">
                <span class="icon is-small"><i class="fa fa-reply"/></span>
              </a>
              <a class="level-item">
                <span class="icon is-small"><i class="fa fa-retweet"/></span>
              </a>
              <a class="level-item">
                <span class="icon is-small"><i class="fa fa-heart"/></span>
              </a>
            </div>
          </nav>
        </div>
      </article>
    </div>
  </section>
</template>

<style>
.media {
  width: 30rem;
  box-shadow: 0 2px 3px #5861d3, 0 0 0 1px #5861d3;
}

.at-twitter-link {
  color: #1c94e0;
}

.container {
  min-height: 80vh;
  display: flex;
  justify-content: center;
  font-family: 'Skia-Regular_Black';
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

.holidays-logo-position {
  position: relative;
  top: 1rem;
}

.index-wrap {
  position: relative;
  top: 7rem;
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

.at-twitter-link {
  color: #1c94e0;
}
</style>
