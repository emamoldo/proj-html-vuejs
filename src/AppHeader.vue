<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <div class="header">
        <img class="logo" src="/src/assets/img/logo.png" alt="">

        <div class="utilities">
            <a href="#">Home</a>
            <a href="#">Apple</a>
            <a href="#">Microsoft</a>
            <a href="#">Android</a>
            <a href="#">Forums</a>
            <a href="#">Contact Us</a>
            <button class="header_btn" type="button">Join Us</button>
            <i class="fa-solid fa-magnifying-glass"></i>
        </div>
    </div>
</template>


<style>
/* Header Section */
.header {
    background-color: var(--bool-bg-header);
    align-items: center;
    display: flex;
    justify-content: space-around;
    padding: 1rem;

    .utilities {
        display: flex;
        color: var(--bool-white);
        gap: 2rem;
        align-items: center;

        a {
            text-decoration: none;
            color: var(--bool-white);
        }

        .header_btn {
            background-color: var(--bool-text-btn);
            color: var(--bool-white);
            border: none;
            padding: 0.5rem;
        }
    }
}
</style>
