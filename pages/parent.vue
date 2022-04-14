<template lang="pug">
    section
        b-container
            h1
                | I am the parent view
            nav
                ul
                    li
                        NuxtLink(to="/parent/child")
                            | Child
                    li
                        NuxtLink(to="/parent/child2")
                            | Child 2
            NuxtChild
</template>
<style lang="scss" scoped></style>
