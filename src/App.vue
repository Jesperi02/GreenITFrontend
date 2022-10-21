<script lang="ts">
import { defineComponent } from 'vue';
import BadFileUpload from './components/BadFileUpload.vue';

export default defineComponent({
  name: 'App',
  components: {
    BadFileUpload
  }
});
</script>

<template>
    <h1>Here is a child component!</h1>
    <BadFileUpload/>
</template>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<style lang="scss">
    @import 'src/styles/App';
</style>