<template>

    <div>
        <div class="card mb-5 text-center text-white hovereffect">
            <img class="card-img-top" src="../assets/halteres-musculation.jpg" alt="Card image" style="min-height: 200px">
            <div class="card-img overlay">
                <div>
                    <h2 class="card-title display-3" style="font-size:5vw;">BODY MONSTERS <strong class="text-warning display-2 font-weight-bold" style="font-size:5vw;">Events</strong></h2>
                    <a class="btn btn-outline-warning info" style="font-size:2vw;">Join US</a>
                </div>
            </div>
        </div>
    </div>


</template>

<script>
    import {mdbBtn } from 'mdbvue';
    export default {
        name: "JoinUs",
            components: {
            mdbBtn
        }
    }
</script>

<style scoped>
    .hovereffect {
        width: 100%;
        height: 100%;
        float: left;
        overflow: hidden;
        position: relative;
        text-align: center;
        cursor: default;
    }

    .hovereffect .overlay {
        width: 100%;
        height: 100%;
        position: absolute;
        overflow: hidden;
        top: 0;
        left: 0;
        background-color: rgba(50,50,50,0.6);
        -webkit-transition: all 0.4s  cubic-bezier(0.88,-0.99, 0, 1.81);
        transition: all 0.4s  cubic-bezier(0.88,-0.99, 0, 1.81);
    }

    .hovereffect:hover .overlay {
        background-color: rgba(170,170,170,0.4);
    }

    .hovereffect img {
        display: block;
        position: relative;
    }

    .hovereffect h2 {
        text-transform: uppercase;
        color: #fff;
        text-align: center;
        position: relative;
        /*font-size: 17px;*/
        margin-top: 50px;
        padding: 5px;
        background: rgba(0, 0, 0, 0.6);
        -webkit-transform: translateY(45px);
        -ms-transform: translateY(45px);
        transform: translateY(45px);
        -webkit-transition: all 0.4s  cubic-bezier(0.88,-0.99, 0, 1.81);
        transition: all 0.4s  cubic-bezier(0.88,-0.99, 0, 1.81);
    }

    .hovereffect:hover h2 {
        -webkit-transform: translateY(px);
        -ms-transform: translateY(5px);
        transform: translateY(5px);
    }

    .hovereffect a.info {
        display: inline-block;
        text-decoration: none;
        padding: 7px 14px;
        text-transform: uppercase;
        color: #fff;
        border: 1px solid #fff;
        background-color: transparent;
        opacity: 0;
        filter: alpha(opacity=0);
        -webkit-transform: scale(0);
        -ms-transform: scale(0);
        transform: scale(0);
        -webkit-transition: all 0.4s  cubic-bezier(0.88,-0.99, 0, 1.81);
        transition: all 0.4s  cubic-bezier(0.88,-0.99, 0, 1.81);
        font-weight: normal;
        margin: -140px 0 0 0;
        padding: 180px 660px;
    }

    .hovereffect:hover a.info {
        opacity: 1;
        filter: alpha(opacity=100);
        -webkit-transform: scale(1);
        -ms-transform: scale(1);
        transform: scale(1);
    }

    .hovereffect a.info:hover {
        box-shadow: 0 0 5px #fff;
    }
</style>
