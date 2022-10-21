<script lang="ts">
    import { defineComponent } from 'vue';
    import FileUpload from './components/FileUpload.vue';
    import FileShow from './components/FileShow.vue';

    export default defineComponent({
        name: 'App',
        components: {
            FileUpload,
            FileShow
        }
    });
</script>

<template>
    <div class="content">
        <FileUpload/>
        <FileShow/>
    </div>
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