<script setup lang="ts">
</script>

<template>
    <header>
        <img alt="splab logo" class="logo" src="../assets/splab-logo.png" width="320" height="77" />
        <h1>Re:Member</h1>
    </header>
    <div class="header-spacer"></div>
</template>

<style scoped>
header {
    line-height: 1.5;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    padding-top: 6px;
    padding-bottom: 6px;
    padding-left: 24px;
    padding-right: 24px;
}

header h1 {
    color: #616161;
}

.logo {
    display: block;
    margin: 0 auto;
}

.header-spacer {
    height: 2rem;
    background-color: #84a2d4;
}

@media (min-width: 1024px) {
    header {
        display: flex;
        place-items: center;
    }

    .logo {
        margin: 0 2rem 0 0;
    }
}
</style>