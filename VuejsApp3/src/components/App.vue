<template>
  <div id="app">
    <input
      v-model="message"
      type="text">
      <h2 class="message">{{ message }}</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Some dumb new message!!',
    };
  },
};
</script>

<style>
.message {
  font-size: 18px;
  font-family: 'Roboto', sans-serif;
  color: blue;
}
</style>
