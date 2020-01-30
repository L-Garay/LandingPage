<template>
  <div class="app">
    <div class="navbar">
      <nav class="nav flex-column">
        <a class="nav-link active" href="#home">Home</a>
        <a class="nav-link" href="#skills">Skills</a>
        <a class="nav-link" href="#contact">Contact</a>
      </nav>
    </div>
    <div class="master">
      <div id="home" class="container-fluid">
        <div class="row Row">
          <div class="col">
            <img alt="Vue logo" src="../assets/logo.png" />
            <h2 class="pageFiller">This is going to be the 'home' view.</h2>
          </div>
        </div>
      </div>
      <div id="skills" class="container-fluid">
        <div class="row Row">
          <div class="col skillSection">
            <div class="sec1">
              <h2>
                This is going to be the 'second' page; where my skills and
                projects will go. You should be able to scroll either left or
                right, but als have a section that can scroll up and down to view
                different projects.
              </h2>
            </div>
          </div>
        </div>
      </div>
      <div id="contact" class="container-fluid">
        <div class="row Row">
          <div class="col contactSection">
            <h2>
              This is going to be the 'contact' page and last page; where it will
              have all my contact info, links, etc. You should only be able to
              scroll to the left.
            </h2>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
<style>
.app {
  display: flex;
}
.master {
  display: flex;
  flex-direction: column;
  width: 100vw;
  height: 100vh;
  scroll-snap-type: y mandatory;
  overflow-y: scroll;
  scroll-behavior: smooth;
}
.Row {
  height: 100vh;
  scroll-snap-align: start;
}
</style>
