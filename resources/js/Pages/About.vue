<template>
    <div>
        <h1>About Page {{ users }}</h1>
    </div>
</template>

<script setup>
defineProps({
    users: String,
});
</script>
