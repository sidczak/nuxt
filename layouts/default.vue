<template lang="pug">
.d-flex.flex-column.h-100
    header
        Navbar
    main.flex-shrink-0
        Nuxt
    footer.footer.mt-auto.py-3.bg-light
        b-container
            span.float-right
                a(href="#")
                    | Back to top
            span
                | &copy; 2017-2018 Company, Inc. &middot; <a href="#">Privacy</a> &middot; <a href="#">Terms</a>
</template>

<style>
/*a.nuxt-link-active {
    font-weight: bold;
    color: red !important;
}*/
/*a.nuxt-link-exact-active {
    color: orange !important;
}*/
.page-enter-active,
.page-leave-active {
    transition: opacity 0.5s;
}
.page-enter,
.page-leave-active {
    opacity: 0;
}
</style>
