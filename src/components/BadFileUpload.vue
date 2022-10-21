<template>
    <div class="content">
        <div class="box">

        </div>

        <button @click="count++">You clicked me {{ count }} times.</button>
    </div>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        data() {
            return {
                count: 0
            }
        }
    });
</script>