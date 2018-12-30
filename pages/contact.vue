<template>
  <section class="container is-center">
    <div class="index-wrap">
      <div class="card">
        <div class="card-image">
          <figure class="image is-4by3">
            <img
              src="https://bulma.io/images/placeholders/1280x960.png"
              alt="Placeholder image">
          </figure>
        </div>
        <div class="card-content">
          <div class="media">
            <div class="media-left">
              <figure class="image is-48x48">
                <img
                  src="https://bulma.io/images/placeholders/96x96.png"
                  alt="Placeholder image">
              </figure>
            </div>
            <div class="media-content">
              <p class="title is-4">John Smith</p>
              <p class="subtitle is-6">@johnsmith</p>
            </div>
          </div>

          <div class="content">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Phasellus nec iaculis mauris. <a>@bulmaio</a>.
            <a href="#">#css</a> <a href="#">#responsive</a>
            <br>
            <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
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
