<script>
  let src = "./images/Screens.png";
  let src2 = "./images/Screens1.png";
  import MyNavbar from "../components/MyNavbar.svelte";
</script>

<style>
  .banner-bg {
    z-index: -2222;
    position: absolute;
    overflow-y: hidden;
    /* border: 2px solid red; */
    top: 0;
    display: flex;
    flex-direction: row;
    width: 101.1%;
    height: 100vh;
    margin-top: -0.5rem;
    margin-left: -0.5em;
  }
  .left {
    background-color: rgba(255, 255, 255, 0.315);
    padding-right: 40em;
    padding-bottom: 55em;
    overflow-y: hidden;

    clip-path: polygon(0 0, 100% 0, 9% 100%, 0% 100%);
  }
  .left-div {
    width: 50%;
    padding: 0;
    margin: 0;
    filter: drop-shadow(21px 60px 22px rgba(19, 19, 17, 0.514));
  }

  .right {
    z-index: -2222;
    width: inherit;
    padding-bottom: 49em;
    /* clip-path: polygon(61% 0, 100% 0, 100% 100%, 0 100%); */
    /* clip-path: polygon(35% 0, 100% 0%, 100% 100%, 0 100%); */
    /* clip-path: polygon(40% 0, 100% 0%, 100% 100%, 0 100%); */
    /* clip-path: polygon(46% 0, 100% 0%, 100% 100%, 0 100%); */
    clip-path: polygon(48% 0, 100% 0%, 100% 100%, 0 100%);
    /* width: 200%; */
    padding-left: 3em;
    background-color: #036564;
  }
  .banner-top {
    z-index: 10000000;
    position: absolute;
    padding: 1em;

    width: 100%;
    height: 100vh;
  }
  .img-btm {
    width: 44%;
    margin-top: 7em;
    margin-left: 26em;
  }
  .img-top {
    margin-left: 53em;
    margin-top: 12em;
    z-index: 100000;
    border: 2px solid red;
  }
</style>

<div class="banner">
  <div class="banner-bg">
    <div class="left-div">
      <span class="left" />
    </div>
    <div class="right">
      <img class="img-btm" {src} alt="screens" />
      <img class="img-top" {src2} alt="screens" />
    </div>

  </div>

  <div class="banner-top">
    <MyNavbar />

  </div>
</div>
