<template>
  <button v-if="!show" @click="show = true">Play</button>
  <div v-if="show">
    <h1>v1</h1>

  <div class="grid">
    <div class="wrap">
      <div class="number">1</div>

      <div class="video">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/J6G0EuPAoKQ"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">2</div>

      <div class="video">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/J6G0EuPAoKQ?autoplay=1"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">3</div>

      <div class="video">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/J6G0EuPAoKQ?loop=1&amp;playlist=J6G0EuPAoKQ&amp;autoplay=1&amp;"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">4</div>

      <div class="video">
        <iframe
          frameborder="0"
          allowfullscreen="1"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          title="YouTube video player"
          width="560"
          height="315"
          src="https://www.youtube.com/embed/J6G0EuPAoKQ?origin=http%3A%2F%2Flocalhost%3A8080&amp;enablejsapi=1&amp;autoplay=1&amp;autohide=1&amp;modestbranding=1&amp;disablekb=1&amp;controls=0&amp;playsinline=1&amp;loop=1&amp;widgetid=1"
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">5</div>

      <div class="video">
        <iframe
          frameborder="0"
          allowfullscreen="1"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          title="YouTube video player"
          width="560"
          height="315"
          src="https://www.youtube.com/embed/J6G0EuPAoKQ?origin=http%3A%2F%2Flocalhost%3A8080&amp;enablejsapi=1&amp;autoplay=1&amp;autohide=1&amp;modestbranding=1&amp;disablekb=1&amp;controls=0&amp;playsinline=1&amp;loop=1&amp;playlist=J6G0EuPAoKQ&amp;widgetid=5"
          id="widget6"
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">6</div>

      <div class="video">
        <iframe
          frameborder="0"
          allowfullscreen="1"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          title="YouTube video player"
          width="560"
          height="315"
          src="https://www.youtube.com/embed/J6G0EuPAoKQ?origin=http%3A%2F%2Flocalhost%3A8080&amp;autoplay=1&amp;controls=0&amp;playsinline=1&amp;loop=1&amp;playlist=J6G0EuPAoKQ&amp;widgetid=5"
          id="widget6"
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">7</div>

      <div class="video">
        <iframe
          frameborder="0"
          allowfullscreen="1"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          title="YouTube video player"
          width="560"
          height="315"
          src="https://www.youtube.com/embed/J6G0EuPAoKQ?origin=http%3A%2F%2Flocalhost%3A8080&amp;autoplay=1&amp;controls=0&amp;loop=1&amp;playlist=J6G0EuPAoKQ&amp;"
          id="widget6"
        ></iframe>
      </div>
    </div>
  </div>

  <h1>v2</h1>

  <div class="grid">
    <div class="wrap">
      <div class="number">1</div>

      <div class="video">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube-nocookie.com/embed/J6G0EuPAoKQ"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">2</div>

      <div class="video">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube-nocookie.com/embed/J6G0EuPAoKQ?autoplay=1"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">3</div>

      <div class="video">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube-nocookie.com/embed/J6G0EuPAoKQ?loop=1&amp;playlist=J6G0EuPAoKQ&amp;autoplay=1&amp;"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">4</div>

      <div class="video">
        <iframe
          frameborder="0"
          allowfullscreen="1"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          title="YouTube video player"
          width="560"
          height="315"
          src="https://www.youtube-nocookie.com/embed/J6G0EuPAoKQ?origin=http%3A%2F%2Flocalhost%3A8080&amp;enablejsapi=1&amp;autoplay=1&amp;autohide=1&amp;modestbranding=1&amp;disablekb=1&amp;controls=0&amp;playsinline=1&amp;loop=1&amp;widgetid=1"
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">5</div>

      <div class="video">
        <iframe
          frameborder="0"
          allowfullscreen="1"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          title="YouTube video player"
          width="560"
          height="315"
          src="https://www.youtube-nocookie.com/embed/J6G0EuPAoKQ?origin=http%3A%2F%2Flocalhost%3A8080&amp;enablejsapi=1&amp;autoplay=1&amp;autohide=1&amp;modestbranding=1&amp;disablekb=1&amp;controls=0&amp;playsinline=1&amp;loop=1&amp;playlist=J6G0EuPAoKQ&amp;widgetid=5"
          id="widget6"
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">6</div>

      <div class="video">
        <iframe
          frameborder="0"
          allowfullscreen="1"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          title="YouTube video player"
          width="560"
          height="315"
          src="https://www.youtube-nocookie.com/embed/J6G0EuPAoKQ?origin=http%3A%2F%2Flocalhost%3A8080&amp;autoplay=1&amp;controls=0&amp;playsinline=1&amp;loop=1&amp;playlist=J6G0EuPAoKQ&amp;widgetid=5"
          id="widget6"
        ></iframe>
      </div>
    </div>

    <div class="wrap">
      <div class="number">7</div>

      <div class="video">
        <iframe
          frameborder="0"
          allowfullscreen="1"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          title="YouTube video player"
          width="560"
          height="315"
          src="https://www.youtube-nocookie.com/embed/J6G0EuPAoKQ?origin=http%3A%2F%2Flocalhost%3A8080&amp;autoplay=1&amp;controls=0&amp;loop=1&amp;playlist=J6G0EuPAoKQ&amp;"
          id="widget6"
        ></iframe>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
  data() {
    return {
      show: false
    }
  },
  created() {
    // setTimeout(() => {
    //   this.show = true
    // }, 3000)
  }
};
</script>

<style scoped>
.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}

.number {
  font-size: 32px;
}
</style>