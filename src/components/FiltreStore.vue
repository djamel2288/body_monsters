<template>
    <div class="sticky-top">
        <Menu/>
        <mdb-navbar expand="xl" hamburger class="black" dark togglerIcon="filter text-warning">
            <!-- Navbar brand -->
            <mdb-navbar-brand class="text-white"></mdb-navbar-brand>
            <mdb-navbar-toggler>
                <mdb-navbar-nav center>
                    <form class="p-3  border-warning border-bottom">
                        <div class="custom-control custom-switch text-center text-white">
                        <span>
                            <input type="checkbox" class="custom-control-input" id="customSwitch0" v-model="all_products">
                            <label class="custom-control-label mx-5" for="customSwitch0"> Men <b>(Checked: {{ all_products }})</b></label>
                        </span>

                            <span>
                            <input type="checkbox" class="custom-control-input" id="customSwitch1" v-model="products">
                            <label class="custom-control-label mx-5" for="customSwitch1"> Men <b>(Checked: {{ products }})</b></label>
                        </span>

                            <span>
                            <input type="checkbox" class="custom-control-input" id="customSwitch2" v-model="women">
                            <label class="custom-control-label mx-5" for="customSwitch2"> 000 <b>(Checked: {{ women }})</b></label>
                        </span>

                            <span>
                            <input type="checkbox" class="custom-control-input" id="customSwitch3" v-model="men">
                            <label class="custom-control-label mx-5" for="customSwitch3"> 000 <b>(Checked: {{ men }})</b></label>
                        </span>

                        </div>
                    </form>
                </mdb-navbar-nav>
            </mdb-navbar-toggler>
        </mdb-navbar>
        <!--/.Navbar-->

    </div>
</template>

<script>
    import { mdbNavbar, mdbNavItem, mdbNavbarNav, mdbNavbarToggler, mdbContainer, mdbRow, mdbInput, mdbNavbarBrand, mdbIcon } from 'mdbvue';
    import Menu from "@/components/Menu";
    export default {
        name: "FiltreStore",
        data() {
            return {
                all_products: true,
                products: false,
                women: false,
                men: false
            }
        },
        components:{
            Menu,
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
    input[type="checkbox"].onlinecheckbox + label {
        color: #000000;
    }

    input[type="checkbox"].onlinecheckbox:checked + label {
        color: #cab111;
    }
</style>
