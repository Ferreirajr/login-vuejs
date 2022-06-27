<template >
<div class="vh-100 vw-100 ">
    <main class="form-signin">
        <form>
            <a href="/"><img class="mb-4" src="../assets/logo.png" alt="" width="72" height="70"></a>
            
            <h1 class="h3 mb-3 fw-normal">
                <font style="vertical-align: inherit;">
                    <font style="vertical-align: inherit;">Login</font>
                </font>
            </h1>

            <div class="form-floating">
                <input type="email" class="form-control" id="floatingInput" placeholder="nome@exemplo.com">
                <label for="floatingInput">
                    <font style="vertical-align: inherit;">
                        <font style="vertical-align: inherit;">Endereço de email</font>
                    </font>
                </label>
            </div>
            <div class="form-floating">
                <input type="password" class="form-control" id="floatingPassword" placeholder="Senha">
                <label for="floatingPassword">
                    <font style="vertical-align: inherit;">
                        <font style="vertical-align: inherit;">Senha</font>
                    </font>
                </label>
            </div>
            <button class="w-100 btn btn-md btn-success mt-4 mb-2" type="submit">
                <font style="vertical-align: inherit;">
                    <font style="vertical-align: inherit;">Entrar</font>
                </font>
            </button>
            <small>Ou</small>
            <button class=" w-100 btn btn-md btn-outline-dark mt-2" @click="$router.push('register')"> Crie sua conta</button>
        </form>
    </main>
</div>
</template>
<script>
export default {
    name: "SingIn"

}
</script>
<style>
.form-signin {
    max-width: 360px;
    padding: 20px;
    margin: auto;
    background-color: rgb(236, 252, 242);
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