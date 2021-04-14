<template>
  <header :class="scrollActive ? 'active' : null">
    <div class="navbar container">
      <div class="toggle">
        <button>Menu</button>
      </div>
      <div class="brand">
        <router-link to="/">
          <img src="../assets/logo.png" alt="" />
        </router-link>
      </div>

      <nav>
        <ul class="menu ">
          <li class="menu__items">
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
  props: {
    scrollActive: Boolean
  }
};
</script>
<style scoped>
header {
  position: fixed;
  width: 100%;
  border-bottom: 1px solid #cccccc;
}
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  text-transform: uppercase;
}
.toggle {
  display: none;
}
@media (max-width: 767px) {
  .navbar ul {
    display: none;
  }
}

@media (max-width: 767px) {
  .toggle {
    display: inline-block;
    /* position: absolute; */
    cursor: pointer;
  }
}

.active {
  background-color: rgba(0, 0, 0, 0.692);
  border-bottom: none;
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
  font-size: 18px;
  font-weight: 600;
  color: white;
  /* font-family: "Josefin Sans", sans-serif; */
  border: 3px solid white;
  background-color: transparent;
  cursor: pointer;
  width: 143px;
  outline: none;
}
.btn:hover {
  box-shadow: 0px 0px 15px currentcolor;
  background-color: palevioletred;
  border: 2px solid gray;
}
.menu li {
  padding: 30px;
}
</style>
