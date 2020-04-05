<template>
  <div>
    <center>
      <h1 class="title is-1">Package</h1>
    </center>
    <br />
    <br />
    <div class="tile is-ancestor">
      <div class="tile is-vertical is-8">
        <div class="tile">
          <div class="tile is-parent is-vertical">
            <article class="tile is-child notification is-info">
              <center>
                <p class="title">Player Bundle</p>
              </center>
              <p class="subtitle">Top tile</p>
              <center>
                <a class="button">Find out more</a>
              </center>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child notification is-primary">
              <center>
                <p class="title">TV Combo Bundle</p>
              </center>
              <p class="subtitle">150+ channels</p>
              <p class="subtitle">
                Catch Up & On Demand
                Up to 100Mbps fibre
                Made for 1-4 devices
              </p>
              <p class="subtitle">Up to 100Mbps fibre</p>
              <p class="subtitle">Made for 1-4 devices</p>
              <center>
                <a class="button">Find out more</a>
              </center>
            </article>
          </div>
        </div>
      </div>
      <div class="tile is-parent">
        <article class="tile is-child notification is-success">
          <div class="content">
            <center>
              <p class="title">Full House Bundle</p>
            </center>
            <p class="subtitle">With even more content</p>
            <center>
              <a class="button">Find out more</a>
            </center>
            <div class="content">
              <br />
              <br />
              <!-- Content -->
            </div>
          </div>
        </article>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style >
.button {
  position: relative;
  background-color: #4caf50;
  border: none;
  font-size: 28px;
  color: #ffffff;
  padding: 20px;
  width: 200px;
  text-align: center;
  transition-duration: 0.4s;
  text-decoration: none;
  overflow: hidden;
  cursor: pointer;
}

.button:after {
  content: "";
  background: #f1f1f1;
  display: block;
  position: absolute;
  padding-top: 300%;
  padding-left: 350%;
  margin-left: -20px !important;
  margin-top: -120%;
  opacity: 0;
  transition: all 0.8s;
}

.button:active:after {
  padding: 0;
  margin: 0;
  opacity: 1;
  transition: 0s;
}
</style>