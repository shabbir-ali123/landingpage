<template>
  <header :class="active ? 'active' : null">
    <div class="navbar container">
      <div class="brand">
        <router-link to="/">
          <img src="../assets/logo.png" alt="" />
        </router-link>
      </div>

      <nav>
        <ul class="head ">
          <li>
            <router-link to="/">
              home
            </router-link>
          </li>
          <li>
            <router-link to="/appointments">
              appointments
            </router-link>
          </li>

          <li>
            <router-link to="/contact">
              Contact us
            </router-link>
          </li>
          <button class="btn">book online</button>
        </ul>
      </nav>
    </div>
  </header>
</template>
<script>
export default {
  props: ["active"]
};
</script>
<style scoped>
header {
  position: fixed;
  width: 100%;
  /* border-bottom: 1px solid #cccccc; */
}
.active {
  background-color: rgba(0, 0, 0, 0.692);
  color: aqua;
}
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  text-transform: uppercase;
}
.navbar .brand img {
  width: 120px;
}
ul {
  list-style-type: none;
  display: flex;
  align-items: center;
}
a {
  color: #fff;
}
.btn {
  height: 38px;
  text-transform: capitalize;
  font-size: large;
  color: white;
  font-family: "Josefin Sans", sans-serif;
  border: 3px solid white;
  background-color: transparent;
  cursor: pointer;
  width: 143px;
  box-shadow: 0px 0px 15px currentcolor;
}
.btn:hover {
  background-color: black;
  border: 2px solid gray;
}
.head li {
  padding: 30px;
}
</style>
