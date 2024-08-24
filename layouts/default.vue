<template>
    <div class="wrapper">
        <!-- Header -->
        <header>
            <img src="~/assets/images/logo.svg" alt="">
            <h2>this is header</h2>
            <NuxtLink to="/">home</NuxtLink>
            <br>
            <NuxtLink to="/product">product</NuxtLink>
        </header>
        <!-- Header end -->

        <slot />
    </div>
</template>