<template>
  <div>
    <h1>Person</h1>
      <label for="name">Nome
        <input
        type="text"
        v-model="name"
        placeholder="Informe seu nome">
      </label>

      <hr>
      {{name}}

      <br>
      <label for="email">Email
        <input
        type="email"
        v-model="email"
        placeholder="Informe seu email">
      </label>

      <hr>
      {{email}}

      <br>
      <label for="idade">Idade
        <input
        type="number"
        v-model="age"
        placeholder="Informe sua idade">
      </label>

      <hr>
      {{age}}

      <br>
      <label for="bio">Bio
        <input
        type="text-area"
        v-model="bio"
        placeholder="Informe sua bio">
      </label>

      <hr>
      {{bio}}

  </div>
</template>

<script>
export default {
  name: 'PersonCard',
  data() {
    return {
      name: '',
      email: '',
      age: '',
      bio: '',
      isVisible: false,
    };
  },
};
</script>
