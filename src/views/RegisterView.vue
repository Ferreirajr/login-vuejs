<template>
    <main class="form-signin">
        <form>
            <a href="/"><img class="mb-4" src="../assets/logo.png" alt="" width="72" height="70"></a>
            <h1 class="h3 mb-3 fw-normal">
                <font style="vertical-align: inherit;">
                    <font style="vertical-align: inherit;">Cadastro</font>
                </font>
            </h1>
            <div class="form-floating mb-2">
                <input type="text" class="form-control" id="floatingInput" placeholder="Ex: João Silva">
                <label for="floatingInput">
                    <font style="vertical-align: inherit;">
                        <font style="vertical-align: inherit;">Nome</font>
                    </font>
                </label>
            </div>

            <div class="form-floating mb-2">
                <input type="email" class="form-control" id="floatingInput" placeholder="nome@exemplo.com">
                <label for="floatingInput">
                    <font style="vertical-align: inherit;">
                        <font style="vertical-align: inherit;">E-mail</font>
                    </font>
                </label>
            </div>
            <div class="form-floating mb-2">
                <input type="password" class="form-control" id="floatingPassword" placeholder="Senha">
                <label for="floatingPassword">
                    <font style="vertical-align: inherit;">
                        <font style="vertical-align: inherit;">Senha</font>
                    </font>
                </label>
            </div>
            <button class="w-100 btn btn-md btn-success mt-4 mb-2" type="submit">
                <font style="vertical-align: inherit;">
                    <font style="vertical-align: inherit;">Cadastrar</font>
                </font>
            </button>
            <small>Ou</small>
            <button class=" w-100 btn btn-md btn-primary mt-2" @click="$router.push('login')">Login</button>
        </form>
    </main>
</template>

<style>

.form-signin {
    width: 90%;
    max-width: 360px;
    padding: 20px;
    margin: auto;
    margin-top: 10%;
    background-color: aliceblue;
    border-radius: 10px;

}
.form-signin .form-floating:focus-within {
    z-index: 2;
}

.form-signin input[type="email"] {
    margin-bottom: -1px;
    border-bottom-right-radius: 0;
    border-bottom-left-radius: 0;
}

.form-signin input[type="password"] {
    margin-bottom: 10px;
    border-top-left-radius: 0;
    border-top-right-radius: 0;
}
</style>

<script>
export default {
    name: "RegisterView",
}
</script>