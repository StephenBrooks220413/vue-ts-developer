<template>
  <div class="home">
    <main class="jumbotron img-fluid bg-image text-center">
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
        <div class="d-flex justify-content-center align-items-center h-100">
          <h1 class="display-4 text-white mb-0">Vue.js Developer</h1>
        </div>
      </div>
    </main>
    <br />
    <br />
    <br />
    <h1 class="text-center">
      Greetings From Your Vue.js + TypeScript Web Developer
    </h1>
    <br />
    <br />
    <div class="container">
      <div class="row text-center">
        <div class="col-md-4">
          <img
            src="https://cdn-images-1.medium.com/max/1600/1*ACR0gj0wbx91V_xgURifWg.png"
            alt="vue"
            width="160px"
            class="img-content"
          />
        </div>
        <div class="col-md-4">
          <img
            src="https://th.bing.com/th/id/Ra126892ac2b1f9719d828e62e4e12916?rik=aygODZtZRK4%2fsA&riu=http%3a%2f%2fmspoweruser.com%2fwp-content%2fuploads%2f2016%2f07%2ftypescript-cover-image.jpg&ehk=q5uYjHH1I%2b3IzlZWgXXlIM8SYJspUx9roZkSbgToXbc%3d&risl=&pid=ImgRaw"
            alt="typescript"
            width="160px"
            class="img-content"
          />
        </div>
        <div class="col-md-4">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/1200px-Node.js_logo.svg.png"
            alt="node"
            width="160px"
            class="img-content"
          />
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="card hover-shadow text-center">
            <div class="card-header">
              <i class="fab icon fa-connectdevelop"></i>
            </div>
            <div class="card-body">
              <h4 class="card-title">Build Websites</h4>
              <p class="card-text">
                Using Vue.js with TypeScript and MDB5 for laying out content and
                images. Using Vue makes faster load times and very light weight
                on web browsers.
              </p>
              <a
                href="mailto:stephenbrooks714@gmail.com"
                class="btn btn-primary"
                >Inquire</a
              >
            </div>
            <div class="card-footer text-muted">
              227 Projects Built In Vue.js
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card hover-shadow text-center">
            <div class="card-header">
              <i class="fas icon fa-globe"></i>
            </div>
            <div class="card-body">
              <h4 class="card-title">Hosting</h4>
              <p class="card-text">
                Using Vue.js with TypeScript and MDB5 for laying out content and
                images. Using Vue makes faster load times and very light weight
                on web browsers.
              </p>
              <a
                href="mailto:stephenbrooks714@gmail.com"
                class="btn btn-primary"
                >Inquire</a
              >
            </div>
            <div class="card-footer text-muted">
              87 Sites Managed By Node.js
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card hover-shadow text-center">
            <div class="card-header">
              <i class="fas icon fa-tools"></i>
            </div>
            <div class="card-body">
              <h4 class="card-title">Maintenance</h4>
              <p class="card-text">
                Using Vue.js with TypeScript and MDB5 for laying out content and
                images. Using Vue makes faster load times and very light weight
                on web browsers.
              </p>
              <a
                href="mailto:stephenbrooks714@gmail.com"
                class="btn btn-primary"
                >Inquire</a
              >
            </div>
            <div class="card-footer text-muted">
              Maintaining with Node.js
            </div>
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <HelloWorld />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>

<style>
.home {
  color: teal;
}
main {
  background: url(https://images.unsplash.com/photo-1496171367470-9ed9a91ea931?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: auto;
  padding-top: 50%;
  padding-bottom: 50%;
  width: 100%;
}
.icon {
  font-size: 2.7em !important;
  color: grey;
  opacity: 0.7;
}
.img-content {
  letter-spacing: 32px !important;
}
</style>
