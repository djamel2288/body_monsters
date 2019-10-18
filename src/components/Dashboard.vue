
<template>
    <div class="admin">

        <div class="page-wrapper chiller-theme toggled">
            <a id="show-sidebar" @click="toggle_sidebar" class="btn btn-sm btn-dark" href="#">
                <i class="fas fa-bars"></i>
            </a>
            <nav id="sidebar" class="sidebar-wrapper">
                <div class="sidebar-content">
                    <div class="sidebar-brand">
                        <a href="#" class="text-center">
                            <img src="../assets/logo_BM.png" height="40" alt="">
                        </a>
                        <div id="close-sidebar" @click="toggle_sidebar">
                            <i class="fas fa-times"></i>
                        </div>
                    </div>
                    <div class="sidebar-header">
                        <div class="user-pic">
                            <img class="img-responsive img-rounded" src="https://raw.githubusercontent.com/azouaoui-med/pro-sidebar-template/gh-pages/src/img/user.jpg"
                                 alt="User picture">
                        </div>
                        <div class="user-info">
                              <span class="user-name">Admin
                                <strong>Nimda</strong>
                              </span>
                                            <span class="user-role">Administrator</span>
                                            <span class="user-status">
                                <i class="fa fa-circle"></i>
                                <span>Online</span>
                              </span>
                        </div>
                    </div>
                    <!-- sidebar-header  -->
                    <!--div class="sidebar-search">
                        <div>
                            <div class="input-group">
                                <input type="text" class="form-control search-menu" placeholder="Search...">
                                <div class="input-group-append">
                                      <span class="input-group-text">
                                        <i class="fa fa-search" aria-hidden="true"></i>
                                      </span>
                                </div>
                            </div>
                        </div>
                    </div-->
                    <!-- sidebar-search  -->
                    <div class="sidebar-menu">
                        <ul>
                            <li class="header-menu">
                                <span>General</span>
                            </li>

                            <li  class="sidebar-dropdown">
                                <a href="#" @click="toggle_sidebar_submenu" id="dashboard">
                                    <i class="fa fa-tachometer-alt"></i>
                                    <span>Dashboard</span>
                                    <span class="badge badge-pill badge-warning">New</span>
                                </a>
                                <div id="dashboard_sub" class="sidebar-submenu">
                                    <ul>
                                        <li>
                                            <a href="#">Dashboard 1
                                                <span class="badge badge-pill badge-success">Pro</span>
                                            </a>
                                        </li>
                                        <li>
                                            <a href="#">Dashboard 2</a>
                                        </li>
                                        <li>
                                            <a href="#">Dashboard 3</a>
                                        </li>
                                    </ul>
                                </div>
                            </li>

                            <!--li  class="sidebar-dropdown">
                                <a href="#" id="ecommerce" @click="toggle_sidebar_submenu" >
                                    <i class="fa fa-shopping-cart"></i>
                                    <span>E-commerce</span>
                                    <span class="badge badge-pill badge-danger">3</span>
                                </a>
                                <div id="ecommerce_sub" class="sidebar-submenu">
                                    <ul>
                                        <li>
                                            <a href="#">Products
                                            </a>
                                        </li>
                                        <li>
                                            <a href="#">Orders</a>
                                        </li>
                                        <li>
                                            <a href="#">Credit cart</a>
                                        </li>
                                    </ul>
                                </div>
                            </li>

                            <li class="sidebar-dropdown" >
                                <a href="#"  id="components" @click="toggle_sidebar_submenu" >
                                    <i class="far fa-gem"></i>
                                    <span>Components</span>
                                </a>
                                <div id="components_sub" class="sidebar-submenu">
                                    <ul>
                                        <li>
                                            <a href="#">General</a>
                                        </li>
                                        <li>
                                            <a href="#">Panels</a>
                                        </li>
                                        <li>
                                            <a href="#">Tables</a>
                                        </li>
                                        <li>
                                            <a href="#">Icons</a>
                                        </li>
                                        <li>
                                            <a href="#">Forms</a>
                                        </li>
                                    </ul>
                                </div>
                            </li-->
                            <li class="sidebar-dropdown" >
                                <a href="#"  id="charts" @click="toggle_sidebar_submenu" >
                                    <i class="fa fa-chart-line"></i>
                                    <span>Charts</span>
                                </a>
                                <div id="charts_sub" class="sidebar-submenu">
                                    <ul>
                                        <li>
                                            <a href="#">Pie chart</a>
                                        </li>
                                        <li>
                                            <a href="#">Line chart</a>
                                        </li>
                                        <li>
                                            <a href="#">Bar chart</a>
                                        </li>
                                        <li>
                                            <a href="#">Histogram</a>
                                        </li>
                                    </ul>
                                </div>
                            </li>
                            <!--li class="sidebar-dropdown" >
                                <a href="#"  id="maps" @click="toggle_sidebar_submenu">
                                    <i class="fa fa-globe"></i>
                                    <span>Maps</span>
                                </a>
                                <div id="maps_sub" class="sidebar-submenu">
                                    <ul>
                                        <li>
                                            <a href="#">Google maps</a>
                                        </li>
                                        <li>
                                            <a href="#">Open street map</a>
                                        </li>
                                    </ul>
                                </div>
                            </li-->
                            <li class="header-menu">
                                <span>Extra</span>
                            </li>
                            <!--li>
                                <a href="#">
                                    <i class="fa fa-book"></i>
                                    <span>Documentation</span>
                                    <span class="badge badge-pill badge-primary">Beta</span>
                                </a>
                            </li-->
                            <li>
                                <a href="#">
                                    <i class="fa fa-calendar"></i>
                                    <span>Calendar</span>
                                </a>
                            </li>
                            <!--li>
                                <a href="#">
                                    <i class="fa fa-folder"></i>
                                    <span>Examples</span>
                                </a>
                            </li-->
                        </ul>
                    </div>
                </div>
                <!-- sidebar-content  -->
                <div class="sidebar-footer">
                    <a href="#">
                        <i class="fa fa-bell"></i>
                        <span class="badge badge-pill badge-warning notification">3</span>
                    </a>
                    <a href="#">
                        <i class="fa fa-envelope"></i>
                        <span class="badge badge-pill badge-success notification">7</span>
                    </a>
                    <a href="#">
                        <i class="fa fa-cog"></i>
                        <span class="badge-sonar"></span>
                    </a>
                    <a href="#">
                        <i class="fa fa-power-off"></i>
                    </a>
                </div>
            </nav>
            <!-- page-content  -->
            <main class="page-content bg-danger">
                <MenuDash id="MenuDash"></MenuDash>
                <div id="overlay" class="overlay"></div>
                <div class="container bg-info">

                </div>
            </main>
            <!-- page-content" -->
        </div>

    </div>
</template>

<script>
    import MenuDash from "@/components/MenuDash";
    export default {
        name: "Dashboard",

        components:{
            MenuDash
        },
        methods: {
            activeLink(event) {
                if(event.target.className == "link")
                {
                    event.target.className = "active";
                }
                else
                {
                    event.target.className = "link ";
                }
            },
            toggle_sidebar(){
                $(".page-wrapper").toggleClass("toggled");
            },
            toggle_sidebar_submenu(){
                var id_bar = event.currentTarget.id;
                //console.log(id_bar);
                if (id_bar == 'dashboard')
                {
                    $("#dashboard_sub").toggle(200);
                };
                if (id_bar == 'ecommerce')
                {
                    $("#ecommerce_sub").toggle(200);
                };
                if (id_bar == 'charts')
                {
                    $("#charts_sub").toggle(200);
                };

                if (id_bar == 'maps')
                {
                    $("#maps_sub").toggle(200);
                };

                if (id_bar == 'components')
                {
                    $("#components_sub").toggle(200);
                };
            }
        }
    }
    //import '../assets/admin.js'
</script>

<style scoped>
    @import "../assets/Style/Dashboard.css";
</style>

