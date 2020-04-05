<template>
  <b-carousel
    :arrow="arrow"
    :arrow-both="arrowBoth"
    :arrow-hover="arrowHover"
    :icon-pack="iconPack"
    :icon-prev="iconPrev"
    :icon-next="iconNext"
    :icon-size="iconSize"
  >
    <b-carousel-item v-for="(carousel, i) in carousels" :key="i">
      <section :class="`hero is-medium is-${carousel.color}`">
        <div class="hero-body has-text-centered">
          <div id="navbarExampleTransparentExample" class="navbar-menu">
            <div class="navbar-end">
              <div class="navbar-item has-dropdown is-hoverable">
                <a class="navbar-link" href="https://bulma.io/documentation/overview/start/">Home</a>
                <div class="navbar-dropdown is-boxed">
                  <a class="navbar-item" href="https://bulma.io/documentation/overview/start/">Home1</a>

                  <a class="navbar-item" href="https://bulma.io/documentation/columns/basics/">Home2</a>
                  <a
                    class="navbar-item"
                    href="https://bulma.io/documentation/layout/container/"
                  >Home3</a>
                  <a
                    class="navbar-item"
                    href="https://bulma.io/documentation/form/general/"
                  >Homeboxes</a>
                </div>
              </div>
              <div class="navbar-item has-dropdown is-hoverable">
                <a class="navbar-link" href="https://bulma.io/documentation/overview/start/">Feature</a>
                <div class="navbar-dropdown is-boxed">
                  <a
                    class="navbar-item"
                    href="https://bulma.io/documentation/overview/start/"
                  >Typography</a>

                  <a
                    class="navbar-item"
                    href="https://bulma.io/documentation/columns/basics/"
                  >Shortcodes</a>
                  <a
                    class="navbar-item"
                    href="https://bulma.io/documentation/layout/container/"
                  >Store</a>
                  <a class="navbar-item" href="https://bulma.io/documentation/form/general/">Gallery</a>
                  <a class="navbar-item" href="https://bulma.io/documentation/form/general/">Help</a>
                </div>
              </div>
              <div class="navbar-item has-dropdown is-hoverable">
                <a class="navbar-link" href="https://bulma.io/documentation/overview/start/">About</a>
                <div class="navbar-dropdown is-boxed">
                  <a
                    class="navbar-item"
                    href="https://bulma.io/documentation/overview/start/"
                  >Our Feature</a>

                  <a
                    class="navbar-item"
                    href="https://bulma.io/documentation/columns/basics/"
                  >Our Network</a>
                </div>
              </div>

              <a class="navbar-item" href="https://bulma.io/documentation/overview/start/">Service</a>
              <router-link class="navbar-item" to="/package">Package</router-link>
              <!-- <a class="navbar-item" href="/package">Package</a> -->
              <div class="navbar-item has-dropdown is-hoverable">
                <a class="navbar-link" href="https://bulma.io/documentation/overview/start/">Blog</a>
                <div class="navbar-dropdown is-boxed">
                  <a
                    class="navbar-item"
                    href="https://bulma.io/documentation/form/general/"
                  >All posts</a>
                  <a
                    class="navbar-item"
                    href="https://bulma.io/documentation/form/general/"
                  >Classic Style</a>
                  <a
                    class="navbar-item"
                    href="https://bulma.io/documentation/form/general/"
                  >Portfolio</a>
                  <a class="navbar-item" href="https://bulma.io/documentation/form/general/">Chess</a>
                </div>
              </div>
              <a
                class="navbar-item"
                href="https://bulma.io/documentation/overview/start/"
              >Get in touch</a>
              <a>
                <button class="button is-primary is-rounded">GET START</button>
              </a>
            </div>

            <div class="navbar-end">
              <div class="navbar-item">
                <div class="field is-grouped"></div>
              </div>
            </div>
          </div>
          <h1 class="title is-1">Made for entertainment</h1>
          <h1 class="title is-1">Great Broadband</h1>
          <br />

          <h1 class="title is-1">>at a Great Price</h1>
          <br />
          <h1>
            >
            With an extra
            <i>5GB</i> every month –
          </h1>

          <br />

          <h2>
            worth
            <i
              data-stylerecorder="true"
              style="text-align: left; letter-spacing: 0px; font-weight: 700; border-color: rgb(255, 255, 255); border-style: none; margin: 0px; border-radius: 0px; padding: 0px;"
            >$10</i> a month!
          </h2>
        </div>
      </section>
    </b-carousel-item>
  </b-carousel>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      carousel: 0,
      animated: "fade",
      drag: false,
      autoPlay: false,
      pauseHover: false,
      pauseInfo: false,
      repeat: false,
      pauseType: "is-primary",
      interval: 3000,
      carousels: [
        { title: "Slide 1", color: "dark" },
        { title: "Slide 2", color: "primary" },
        { title: "Slide 3", color: "info" },
        { title: "Slide 4", color: "success" },
        { title: "Slide 5", color: "warning" },
        { title: "Slide 6", color: "danger" }
      ]
    };
  }
};
</script>

<style >
.light {
  line-height: inherit;
  font-weight: inherit;
  font-size: inherit;
  width: auto;
  margin: 0;
}
.bigfont {
  font-size: large;
}
</style>
