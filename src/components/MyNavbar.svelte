<script>
  let src = "./images/Group 1.png";
</script>

<style>
  .navbar {
    margin-top: 1.2em;

    /* border: 2px solid red; */

    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }
  .menus {
    /* border: 2px solid red; */

    z-index: 10000;
    margin-left: 27em;
  }
  a {
    /* z-index: 10000000; */
    color: #036564;
    text-decoration: none;
    /* margin-left: 6em; */
    padding-left: 4em;
    font-size: 1.2em;
  }
  .white-menu {
    color: white;
    z-index: 1000000;
  }
  input {
    /* border: 2px solid red; */
    background-color: #031634;
    outline: none;
    border: none;
  }
  ::placeholder {
    /* border: 2px solid red; */
    color: whitesmoke;
    font-weight: bold;
  }
</style>

<div class="navbar">
  <img {src} alt="kite logo" />
  <div class="menus">
    <a href="http://localhost:5000/">About.</a>
    <a href="http://localhost:5000/">Get Tickets.</a>
    <a class="white-menu" href="http://localhost:5000/">My keti.</a>
  </div>
  <input placeholder="Dar es salaaam,TZ|EN" type="text" />
</div>
