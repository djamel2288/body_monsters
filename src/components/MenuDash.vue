<template>
    <mdb-navbar expand="xl" hamburger class="bg-dark" togglerIcon="ellipsis-v text-warning">
        <!-- Navbar brand -->
        <mdb-navbar-brand class="text-white"></mdb-navbar-brand>
        <mdb-navbar-toggler>
            <mdb-navbar-nav center>

            </mdb-navbar-nav>
        </mdb-navbar-toggler>
    </mdb-navbar>
</template>

<script>
    import { mdbNavbar, mdbNavItem, mdbNavbarNav, mdbNavbarToggler, mdbContainer, mdbRow, mdbInput, mdbNavbarBrand, mdbIcon } from 'mdbvue';
    export default {
        name: "MenuDash",
        components:{
            mdbNavbar,
            mdbNavItem,
            mdbNavbarNav,
            mdbNavbarToggler,
            mdbContainer,
            mdbRow,
            mdbInput,
            mdbNavbarBrand,
            mdbIcon
        }
    }
</script>

<style scoped>

</style>
