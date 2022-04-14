<template lang="pug">
    b-navbar(toggleable="lg" type="dark" variant="info" fixed="top")
        b-navbar-brand(to="/")
          | HomeNuxt
        b-navbar-toggle(target="nav-collapse")

        b-collapse(id="nav-collapse" is-nav)
            b-navbar-nav
                b-nav-item(to="/")
                    | Home
                b-nav-item(to="/about")
                    | About
                b-nav-item(to="/pricing")
                    | Pricing
                b-nav-item(to="/parent")
                    | Parent
            b-navbar-nav(class="ml-auto")
                b-nav-item-dropdown(text="Lang" right)
                    b-dropdown-item(href="#") EN
                    b-dropdown-item(href="#") PL
</template>
