<template>
  <div id="app">
    <Home
      msg="Seja bem vindo(a), certifique-se de ler as instruções na página do github do desafio."
    />
  </div>
</template>

<script>
import Home from "./components/Home";

export default {
  name: "App",
  components: {
    Home,
  },
};
</script>

<style>
#app {
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  font: 400 16px Roboto, sans-serif;
}
</style>
