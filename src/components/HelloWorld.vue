<template>
  <div class="row m-2">
    <div class="col-8">
      <div class="card">
        <card class="body">
          <h3>Descrição</h3>
          <p>Projeto desenvolvido para aprendizagem.</p>
          <p></p>
        </card>

      </div>

    </div>
    <div class="col-4">
      <div class="card">
        <h3>Frontend</h3>
        <ul>
          <li>
            <img alt="Vue logo" src="../assets/logo.png" width="40" height="40">
            <p>VueJs</p>
          </li>
          <li>
            <img alt="Bootstrap logo" src="../assets/bootstrap.svg" width="40" height="37">
            <p>Bootstrap 5</p>
          </li>
          <li>
            <img alt="IonIcons logo" src="../assets/ionicons.png" width="40" height="40">
            <p>IonIcons</p>
          </li>
        </ul>
        <h3>Backend</h3>
        <ul>
          <li>
            <img alt="Laravel logo" src="../assets/laravel.png" width="40" height="40">
            <p>Laravel</p>
          </li>
          <li>
            <img alt="Postgres logo" src="../assets/postgres.png" width="40" height="40">
            <p>Postgres</p>
          </li>
          <li>
            <img alt="Docker logo" src="../assets/docker.png" width="40" height="40">
            <p>Docker</p>
          </li>
          <li>
            <img alt="Nginx logo" src="../assets/nginx.webp" width="40" height="40">
            <p>Nginx</p>
          </li>
        </ul>
        <h3>Bibliotecas</h3>
        <ul>
          <li>
            <img alt="JWT logo" src="../assets/jwt.png" width="45" height="39">
            <p>Jwt</p>
          </li>
          <li>
            <img alt="Axios logo" src="../assets/axios.png" width="45" height="25">
            <p>Axios</p>
          </li>
        </ul>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

</style>
