<script setup>
    import { ref } from 'vue';

    let mobileNav = ref(false);

    let toggleMobileNav = () => {
        mobileNav.value = !mobileNav.value
    }
</script>

<template>
    <!-- Navbar Start -->
  <h2>navbar</h2>
    <!-- Navbar End -->
</template>