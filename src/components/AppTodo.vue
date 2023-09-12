<script setup lang="ts">
import AppTitle from './AppTitle.vue'
</script>

<template>
    <div class="todo">
        <AppTitle />
    </div>
</template>

<style scoped lang="scss">
.todo {
    width: 100%;
    max-width: 400px;
    padding: 20px 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #ffffff;
    border: 2px solid #7878e6;
    border-radius: 10px;
}
</style>