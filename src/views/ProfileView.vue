<script setup>
defineProps ({
    user: {
        type: String,
        required: true,
    }
})
</script>

<template>
    <header class="header">
        <p>This is a User's Profile Page.</p>
    </header>
    <main class="main">
        <div class="wrapper">
            <div class="content">
                <p>{{user}}</p>
            </div>
        </div>
    </main>
</template>

<style>
    .header {
        color: bisque;
    }
</style>