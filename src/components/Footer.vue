<template>
        <div>
            <div class="text-center bg-black py-3">
                <a href="#" style="text-decoration: none" class="text-white font-weight-bold mx-3">
                    <i class="m-2 fas fa-map-marker-alt fa-lg text-white"></i>
                    City ********************
                </a>
                <a href="#" style="text-decoration: none" class="text-white font-weight-bold mx-3">
                    <i class="m-2 fas fa-mobile-alt fa-lg text-white"></i>
                    +213-XXX-XXX-XXX / +213-YYY-YYY-YYY
                </a>
                <a href="#" style="text-decoration: none" class="text-white font-weight-bold mx-3">
                    <i class="m-2 fas fa-envelope-open fa-lg text-white"></i>
                    2019 / 2020 Algers, All Rights Reserved
                </a>
            </div>

            <div class="text-center bg-warning ">
                <a href="#" style="text-decoration: none" class="text-danger font-weight-bold">
                    CopyRight Reserved
                    <i class="m-2 far fa-copyright fa-lg text-danger"></i>
                    2019 / 2020 Algers, All Rights Reserved
                </a>
            </div>
        </div>
</template>

<script>
    import { mdbNavbar, mdbNavbarBrand, mdbNavbarToggler, mdbNavbarNav, mdbNavItem, mdbDropdown, mdbDropdownMenu, mdbDropdownToggle, mdbInput, mdbDropdownItem,mdbIcon } from 'mdbvue';
    export default {

        name: "Footer",
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
