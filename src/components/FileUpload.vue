<template>
    <h1>Drop a file to upload it!</h1>
    <div class="box up">
        <button>
             Or click me!
        </button>
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