<template>
  <div id="app">
    <div class="container">
      <nav class="navbar is-transparent">
        <div class="navbar-brand">
          <a class="navbar-item" href="https://bulma.io"></a>
          <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
            <span></span>
            <span></span>
            <span></span>
          </div>
        </div>
      </nav>
      <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <a class="navbar-item" href="https://bulma.io"></a>
          <a
            role="button"
            class="navbar-burger burger"
            aria-label="menu"
            aria-expanded="false"
            data-target="navbarBasicExample"
          >
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>

        <div id="navbarBasicExample" class="navbar-menu">
          <div class="navbar-start">
            <a class="navbar-item">LOGIN</a>
            <strong class="navbar-item">OR</strong>
            <a class="navbar-item">REGISTER</a>
            <div class="navbar-item has-dropdown is-hoverable">
              <div class="navbar-dropdown">
                <a class="navbar-item">About</a>
                <a class="navbar-item">Jobs</a>
                <a class="navbar-item">Contact</a>
                <hr class="navbar-divider" />
                <a class="navbar-item">Report an issue</a>
              </div>
            </div>
          </div>

          <div class="navbar-end">
            <div class="navbar-item">
              <strong>YOUR CART:</strong>
              <a class="navbar-item">0 ITEM</a>
            </div>
            <div class="navbar-item">
              <strong>CUSTOMER SERVICE:</strong>
              <a class="navbar-item">+1(800)123-456</a>
            </div>
          </div>
        </div>
      </nav>

      <!-- router -->
      <router-view />

      <footer class="footer">
        <div class="content has-text-centered">
          <div class="columns is-desktop">
            <div class="column">Welcome to the largest broadband and Internet services provider where you can choose the best plan ever.</div>
            <div class="column">Quick links</div>
            <div class="column">Quick links</div>
            <div class="column">Call now for Services!</div>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>
<script>
export default {
  name: "App"
};
</script>
<style>
</style>
