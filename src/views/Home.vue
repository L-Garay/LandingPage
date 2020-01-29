<template>
  <div class="master">
    <div id="home" class="container-fluid">
      <div class="row Row">
        <div class="col">
          <img alt="Vue logo" src="../assets/logo.png" />
          <h2 class="pageFiller">
            This is going to be the 'home' view; you should be able to only
            scroll to the right.
          </h2>
        </div>
      </div>
    </div>
    <div id="skills" class="conatiner-fluid">
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
.master {
  display: flex;
  flex-direction: row;
  height: 87vh;
  overflow-x: scroll;
  scroll-snap-type: x mandatory;
  scroll-behavior: smooth;
}
.Row {
  width: 100vw;
  scroll-snap-align: start;
}
.sec2 {
  height: 50vh;
  overflow-y: scroll;
  margin-bottom: 15pt;
  border: 2pt solid red;
}
</style>
