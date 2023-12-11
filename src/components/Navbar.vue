<script setup>
import { RouterLink } from 'vue-router';

</script>
<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <RouterLink class="navbar-brand" to="/">
                <img src="../assets/logo.png" style="height: 50px;" alt="">
            </RouterLink>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <RouterLink class="nav-link fs-5 me-4" active-class="active" aria-current="page" to="/">Home</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink class="nav-link fs-5" active-class="active" to="/about">About</RouterLink>
                    </li>

                </ul>
                <ul class="d-flex ms-auto">
                    <li class="nav-item"><button href="" class="btn btn-sm btn-outline-success">Sign Up</button></li>
                    <li class="nav-item"><button href="" class="btn btn-sm btn-outline-primary">Sign In</button></li>
                </ul>
            </div>
    </div>
</nav></template>

<style scoped>
    *{
        font-family: 'Poppins', sans-serif;    }
</style>