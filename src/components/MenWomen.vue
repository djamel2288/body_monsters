<template><!--Zoom effect-->
    <div class="card bg-dark text-white mb-5 mx-3">

        <div class="row">

            <div class="col-md-6 p-0">
                <mdb-view class="zoom overlay w-100" alt="zoom">
                    <a href="">
                        <img src="../assets/men.jpg" class="img-fluid card-img" alt="placeholder">
                        <div class="card-img-overlay">
                            <p class="card-title pt-0 text-center text-white centered" style="font-size: 3vmax;">BODY MONSTERS</p>
                        </div>
                        <mdb-mask flex-center pattern="8"/>
                    </a>
                    </mdb-view>
            </div>

            <div class="col-md-6 p-0">
                <mdb-view class="zoom overlay w-100" alt="zoom">
                    <img src="../assets/women.jpg" class="img-fluid card-img" alt="placeholder">
                    <div class="card-img-overlay">
                        <p class="card-title pt-0 text-center text-white centered" style="font-size: 3vmax;">BODY MONSTERS</p>
                    </div>
                    <mdb-mask flex-center overlay="yellow-slight"/>
                </mdb-view>
            </div>

        </div>

    </div>
</template>

<script>
    import { mdbView, mdbMask } from "mdbvue";
    export default {
        name: "MenWomen",
        components: {
            mdbView,
            mdbMask
        }
    }
</script>

<style scoped>
    .centered {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
</style>
