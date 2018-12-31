<template>
  <section class="container is-center">
    <div class="index-wrap">
      <h1 class="title has-text-purple">
        Holidays Inc.
      </h1>
      <h2 class="subtitle holidays-logo-position">
        Profile Page
      </h2>
      <article class="media media-position">
        <figure class="media-left">
          <p class="image is-64x64">
            <img src="~/assets/1.png">
          </p>
        </figure>
        <div class="media-content">
          <div class="content">
            <p>
              <strong><a
                class="japanese-font-family has-text-thin-glay"
                href="https://twitter.com/arthur_foreign"
                target="”_blank”">アーサー@外資系企業の中の人。</a>
              </strong>
              <br>
              <small>
                <a
                  class="at-twitter-link"
                  href="https://twitter.com/arthur_foreign"
                  target="”_blank”">@arthur_foreign</a>
              </small>
              <br>
              <span class="japanese-font-family">
                こんにちは！アーサー@外資系企業の中の人。です。せっかくなので、自己紹介しますね。僕は、普段外資系企業に勤めつつ、休日は開発して、ブログで稼いで、儲かったお金をFXで運用しています。もうしばらくすると、"元"外資系企業の中の人。となっているかもしれません笑
              </span>
            </p>
          </div>
          <nav class="level is-mobile">
            <div class="level-left">
              <p class="level-item">
                <span class="icon is-small has-text-purple"><i class="fa fa-reply"/></span>
              </p>
              <p class="level-item">
                <span class="icon is-small has-text-purple"><i class="fa fa-retweet"/></span>
              </p>
              <p class="level-item">
                <span class="icon is-small has-text-purple"><i class="fa fa-heart"/></span>
              </p>
            </div>
          </nav>
        </div>
        <div class="media-right"/>
      </article>
      <article class="media media-position">
        <figure class="media-left">
          <p class="image is-64x64">
            <img src="~/assets/1.png">
          </p>
        </figure>
        <div class="media-content">
          <div class="content">
            <p>
              <strong><a
                class="japanese-font-family has-text-thin-glay"
                href="https://twitter.com/arthur_foreign"
                target="”_blank”">アーサー@外資系企業の中の人。</a>
              </strong>
              <br>
              <small>
                <a
                  class="at-twitter-link"
                  href="https://twitter.com/arthur_foreign"
                  target="”_blank”">@arthur_foreign</a>
              </small>
              <br>
              <span class="japanese-font-family">
                僕は、プログラミング言語は開発の手段の1つとしか捉えていません。ですが、一応勉強している・していた言語を紹介したいと思います。Ruby・Python・Java・JavaScript・VBAあたりをやっていました。業務では、Javaをメインに扱っています。趣味では、RubyとJavaScriptとPythonを触ることが多いですね。
              </span>
            </p>
          </div>
          <nav class="level is-mobile">
            <div class="level-left">
              <p class="level-item">
                <span class="icon is-small has-text-purple"><i class="fa fa-reply"/></span>
              </p>
              <p class="level-item">
                <span class="icon is-small has-text-purple"><i class="fa fa-retweet"/></span>
              </p>
              <p class="level-item">
                <span class="icon is-small has-text-purple"><i class="fa fa-heart"/></span>
              </p>
            </div>
          </nav>
        </div>
        <div class="media-right"/>
      </article>
      <article class="media media-position">
        <figure class="media-left">
          <p class="image is-64x64">
            <img src="~/assets/1.png">
          </p>
        </figure>
        <div class="media-content">
          <div class="content">
            <p>
              <strong><a
                class="japanese-font-family has-text-thin-glay"
                href="https://twitter.com/arthur_foreign"
                target="”_blank”">アーサー@外資系企業の中の人。</a>
              </strong>
              <br>
              <small>
                <a
                  class="at-twitter-link"
                  href="https://twitter.com/arthur_foreign"
                  target="”_blank”">@arthur_foreign</a>
              </small>
              <br>
              <span class="japanese-font-family">
                ちなみに、このポートフォリオは、Nuxt.jsで作られています。今流行りのSPAを導入するために使いましたけど、想定よりも学習コストが低く、勉強してから3日間でアプリケーションが完成しました。
              </span>
            </p>
          </div>
          <nav class="level is-mobile">
            <div class="level-left">
              <p class="level-item">
                <span class="icon is-small has-text-purple"><i class="fa fa-reply"/></span>
              </p>
              <p class="level-item">
                <span class="icon is-small has-text-purple"><i class="fa fa-retweet"/></span>
              </p>
              <p class="level-item">
                <span class="icon is-small has-text-purple"><i class="fa fa-heart"/></span>
              </p>
            </div>
          </nav>
        </div>
        <div class="media-right"/>
      </article>
    </div>
  </section>
</template>

<style>
.media {
  width: 22rem;
  box-shadow: 0 2px 3px #5861d3, 0 0 0 1px #5861d3;
}

.at-twitter-link {
  color: #1c94e0;
}

.has-text-thin-glay {
  color: #35495e;
}

.media-position {
  position: relative;
  top: 1rem;
}

.container {
  min-height: 125vh;
  display: flex;
  justify-content: center;
  font-family: 'Skia-Regular_Black';
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

.holidays-logo-position {
  position: relative;
  top: 1rem;
}

.index-wrap {
  position: relative;
  top: 5rem;
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
