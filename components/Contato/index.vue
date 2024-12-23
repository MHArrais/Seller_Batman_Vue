<template>
  <div>
    <div class="title-form">Entre em contato conosco!</div>

    <div class="form-content">
      <div class="form">
        <div class="input-container ic1">
          <input
            id="firstname"
            class="input"
            type="text"
            placeholder=" Primeiro Nome "
          />

          <div class="cut"></div>
          <label for="firstname" class="placeholder"></label>
        </div>

        <div class="input-container ic2">
          <input
            id="lastname"
            class="input"
            type="text"
            placeholder=" Ultimo Nome "
          />

          <div class="cut"></div>
          <label for="lastname" class="placeholder"></label>
        </div>

        <div class="input-container ic2">
          <input id="email" class="input" type="text" placeholder=" Email " />

          <label for="email" class="placeholder"></label>
        </div>

        <button class="button-form">Enviar</button>
      </div>
    </div>
  </div>
</template>

<script>
import "./contato.css";
</script>

<style scoped>
/* Estilos para o componente */
div {
  margin-top: 20px;
}
</style>
