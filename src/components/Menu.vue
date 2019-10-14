<template>
    <mdb-navbar color="black" class="sticky-top border-warning border-bottom" dark>

        <mdb-navbar-brand href="" class="ml-4 mr-1">
            <img src="../assets/logo_BM.png" height="30" alt="">
        </mdb-navbar-brand>

        <mdb-navbar-toggler>

            <mdb-navbar-nav class="text-center">
                <mdb-nav-item href="#">Home</mdb-nav-item>
                <mdb-nav-item href="#">Contacts</mdb-nav-item>
                <mdb-nav-item href="#">Pricing</mdb-nav-item>
            </mdb-navbar-nav>

            <mdb-navbar-nav right class="text-center">
                <mdb-nav-item href="#">
                    <mdb-icon icon="envelope" size="lg" class="text-warning  px-3" aria-hidden="true"/>
                </mdb-nav-item>
                <mdb-nav-item href="#">Login</mdb-nav-item>
            </mdb-navbar-nav>

        </mdb-navbar-toggler>
    </mdb-navbar>
</template>

<script>
    import { mdbNavbar, mdbNavbarBrand, mdbNavbarToggler, mdbNavbarNav, mdbNavItem, mdbDropdown, mdbDropdownMenu, mdbDropdownToggle, mdbInput, mdbDropdownItem,mdbIcon } from 'mdbvue';
    export default {

        name: "Menu",
        components: {
            mdbNavbar,
            mdbNavbarBrand,
            mdbNavbarToggler,
            mdbNavbarNav,
            mdbNavItem,
            mdbDropdown,
            mdbDropdownMenu,
            mdbDropdownToggle,
            mdbDropdownItem,
            mdbInput,
            mdbIcon
        }
    }
</script>

<style scoped>
    .navbarcolor{
        background-color: black;
    }
    .logo{
        max-height: 3vmax;
    }
</style>
