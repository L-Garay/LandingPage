<template>
  <div class="master">
    <div class="container-fluid Container">
      <div class="row Row">
        <div class="col">
          <img alt="Vue logo" src="../assets/logo.png" />
          <h2
            class="pageFiller"
          >This is going to be the 'home' view; you should be able to only scroll to the right.</h2>
        </div>
      </div>
    </div>
    <div class="conatiner-fluid Container">
      <div class="row Row">
        <div class="col skillSection">
          <div class="sec1">
            <h2>This is going to be the 'second' page; where my skills and projects will go. You should be able to scroll either left or right, but als have a section that can scroll up and down to view different projects.</h2>
          </div>
          <div class="sec2">
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ut impedit consectetur doloremque dicta error nobis, deserunt iste soluta. Aut hic sapiente commodi esse ratione itaque necessitatibus sed exercitationem asperiores ex!</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempore magni noat similique eum neque nam velit veniam enim deserunt et exercitationem.</p>
            <h5>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi fugit temporibus perferendis dolorum nulla recusandae distinctio dolores minus asperiores reprehenderit dolore illo accusamus cum commodi, molestias, voluptatibus perspiciatis? Iure, eligendi?</h5>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ut impedit consectetur doloremque dicta error nobis, deserunt iste soluta. Aut hic sapiente commodi esse ratione itaque necessitatibus sed exercitationem asperiores ex!</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempore magni noat similique eum neque nam velit veniam enim deserunt et exercitationem.</p>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ut impedit consectetur doloremque dicta error nobis, deserunt iste soluta. Aut hic sapiente commodi esse ratione itaque necessitatibus sed exercitationem asperiores ex!</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempore magni noat similique eum neque nam velit veniam enim deserunt et exercitationem.</p>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ut impedit consectetur doloremque dicta error nobis, deserunt iste soluta. Aut hic sapiente commodi esse ratione itaque necessitatibus sed exercitationem asperiores ex!</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempore magni noat similique eum neque nam velit veniam enim deserunt et exercitationem.</p>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ut impedit consectetur doloremque dicta error nobis, deserunt iste soluta. Aut hic sapiente commodi esse ratione itaque necessitatibus sed exercitationem asperiores ex!</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempore magni noat similique eum neque nam velit veniam enim deserunt et exercitationem.</p>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ut impedit consectetur doloremque dicta error nobis, deserunt iste soluta. Aut hic sapiente commodi esse ratione itaque necessitatibus sed exercitationem asperiores ex!</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempore magni noat similique eum neque nam velit veniam enim deserunt et exercitationem.</p>
          </div>
          <div class="sec3">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi temporibus animi, velit saepe, eius molestias dolore fugit deleniti cum nulla voluptatum suscipit libero, hic dignissimos provident fuga eveniet molestiae aperiam!
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi temporibus animi, velit saepe, eius molestias dolore fugit deleniti cum nulla voluptatum suscipit libero, hic dignissimos provident fuga eveniet molestiae aperiam!
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid Container">
      <div class="row Row">
        <div class="col contactSection">
          <h2>This is going to be the 'contact' page and last page; where it will have all my contact info, links, etc. You should only be able to scroll to the left.</h2>
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
<style scoped>
.master {
  display: flex;
  flex-direction: row;
  height: 87vh;
  overflow-x: scroll;
}
.Row {
  width: 100vw;
}
.sec2 {
  height: 50vh;
  overflow-y: scroll;
  margin-bottom: 15pt;
  border: 2pt solid red;
}
</style>
