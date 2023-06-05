<template>
  <q-page class="flex flex-center">
    <body>
    <div class="container">
        <h1>
            Login
        </h1>
        <form method="post" action="">
            <div>
                <label for="user">
                  User
                </label>
                <input type="user" name="user" placeholder="Digite seu Login">

            </div>
            <div>
                <label for="password">
                   Senha
                </label>
                <input type="password" name="password" placeholder="Digite sua senha">
            </div>
            <div>
                <button type="submit">
                    Enviar
                </button>

            </div>
        </form>
    </div>

</body>

    <!-- <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    > -->
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
