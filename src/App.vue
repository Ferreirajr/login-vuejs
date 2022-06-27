<template>
  <nav v-if="notIsLoginPage">
    <div class="px-3 py-2 bg-light text-dark">
      <div class="container">
        <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
          <a href="/" class="d-flex align-items-center my-2 my-lg-0 me-lg-auto text-white text-decoration-none">
            <img alt="Vue logo" src="./assets/logo.png" width="40" height="40">
          </a>

          <div class="nav col-12 col-lg-auto my-2 justify-content-center my-md-0 text-small">

            <router-link to="/" class="route">
              <ion-icon class="bi d-block mx-auto mt-2" name="home-outline"></ion-icon>Home
            </router-link>

            <router-link to="categorias"  class="route">
              <ion-icon class="bi d-block mx-auto mt-2" name="file-tray-full-outline"></ion-icon>Categorias
            </router-link>

            <router-link to="produtos"  class="route">
              <ion-icon class="bi d-block mx-auto mt-2" name="reader-outline"></ion-icon>Produtos
            </router-link>
            <router-link to="login"  class="route">
              <ion-icon class="bi d-block mx-auto mt-2" name="person-outline"></ion-icon>Login
            </router-link>
          </div>
        </div>
      </div>
    </div>
  </nav>
  <router-view />
</template>

<script>
export default {
  computed: {
    notIsLoginPage() {
      return this.$route.name !== "login" && this.$route.name !== "register";
    }
  }
}
</script>
<style>
body {
  background-color: #e2e2e2;

}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}

nav {
  background-color: aliceblue;
}

nav a {
  font-weight: bold;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #218f58 !important;
  text-decoration: none;
}

nav a.route{
  padding-right: 15px;
  color: #2c3e50;
}
</style>
