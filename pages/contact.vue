<template>
  <section class="container is-center">
    <div class="index-wrap">
      <h1 class="title has-text-purple">
        Holidays Inc.
      </h1>
      <h2 class="subtitle contact-holidays-logo-position">
        Contact Page
      </h2>
      <div class="card twitter-card-position">
        <div class="card-image">
          <figure class="image is-4by3">
            <img
              src="~/assets/1.png"
              alt="Arthur Image">
          </figure>
        </div>
        <div class="card-content">
          <div class="media">
            <div class="media-content">
              <a
                href="https://twitter.com/arthur_foreign"
                target="”_blank”"
                class="title is-5 japanese-font-family">アーサー@外資系企業の中の人。</a>
              <a
                href="https://twitter.com/arthur_foreign"
                target="”_blank”"
                class="subtitle is-6 at-twitter-link twitter-position-bottom">@arthur_foreign</a>
              <div class="content">
                <p class="japanese-font-family twitter-text-position-bottom">
                  僕はTwitter・ブログ・GitHubで情報発信しています。ボタンをクリックすると見たいページに飛ぶことが出来ます。
                </p>
                <div class="buttons">
                  <a
                    class="button is-purple card-footer-item"
                    href="https://twitter.com/arthur_foreign"
                    target="”_blank”">
                    <span class="icon">
                      <i class="fa fa-twitter has-text-white"/>
                    </span>
                    <span class="has-text-white holidays-font">Twitter</span>
                  </a>
                  <a
                    class="header-button-font card-footer-item"
                    href="http://organics-life.com">
                    <font size="3"><b class="button has-text-white is-purple">Blog</b></font>
                  </a>
                  <a
                    class="button is-purple card-footer-item"
                    href="https://github.com/kskcdsp"
                    target="”_blank”">
                    <span class="icon">
                      <i class="fa fa-github has-text-white"/>
                    </span>
                    <span class="has-text-white holidays-font">GitHub</span>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
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

.index-wrap {
  position: relative;
  top: 7rem;
}

.card {
  width: 25rem;
  box-shadow: 0 2px 3px #5861d3, 0 0 0 1px #5861d3;
}

.is-4by3 {
  border-bottom: 0.5px solid #5861d3;
}

.card-header {
  box-shadow: 0 1px 2px #5861d3;
}

.card-footer {
  border-top: 1px solid #5861d3;
}

.card-footer-item:not(:last-child) {
  border-right: 0px;
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

.contact-holidays-logo-position {
  position: relative;
  top: 1rem;
}

.twitter-card-position {
  position: relative;
  top: 1rem;
}

.twitter-position-bottom {
  position: relative;
  top: 0.5rem;
}

.twitter-text-position-bottom {
  position: relative;
  top: 1rem;
}
</style>
