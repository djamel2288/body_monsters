<template>
    <div class="mx-3 bg-white">
        <div class="text-center">
            <h1 class="pt-5 text-black">CONTACTS</h1>
            <p class="h1 pb-5 text-black">You Can Also Find Us Here</p>
        </div>

        <div class="row">

            <div class="col-lg-6 bg-dark">


                <!--a class="row bg-danger mt-5">
                    <i class="fas fa-map-marker-alt text-white pl-5 pr-3 my-3" style="font-size:3.5vh;"></i>
                    <p class="my-3 text-white font-weight-bold" style="font-size:2vh;">City ...... </p>
                </a>
                <a class="row bg-warning text-center">
                    <i class="fas fa-mobile-alt text-white pl-5 pr-3 my-3" style="font-size:3.5vh;"></i>
                    <p class="my-3 text-white font-weight-bold" style="font-size:2vh;">+213-XXX-XXX-XXX</p>
                </a>
                <a class="row bg-danger">
                    <i class="fas fa-envelope-open text-white pl-5 pr-3 my-3" style="font-size:3.5vh;"></i>
                    <p class="my-3 text-white font-weight-bold" style="font-size:2vh;">bodymonsters@gmail.com</p>
                </a-->
                <!-- Default form contact -->
                <form class="m-5">
                    <p class="h2 text-center mb-4 text-white font-weight-bold">Write To Us</p>

                    <!-- Default input name -->
                    <label for="defaultFormContactNameEx" class="text-white">Your name</label>
                    <input type="text" id="defaultFormContactNameEx" class="form-control">

                    <br>

                    <!-- Default input email -->
                    <label for="defaultFormContactEmailEx" class="text-white">Your email</label>
                    <input type="email" id="defaultFormContactEmailEx" class="form-control">

                    <br>

                    <!-- Default input subject -->
                    <label for="defaultFormContactSubjectEx" class="text-white">Subject</label>
                    <input type="text" id="defaultFormContactSubjectEx" class="form-control">

                    <br>

                    <!-- Default textarea message -->
                    <label for="defaultFormContactMessageEx" class="text-white">Your message</label>
                    <textarea type="text" id="defaultFormContactMessageEx" class="form-control noresize" rows="3"></textarea>

                    <div class="text-center mt-4">
                        <button class="btn btn-outline-warning" type="submit">Send<i class="far fa-paper-plane ml-2"></i></button>
                    </div>
                </form>
                <!-- Default form contact -->

            </div>

            <div class="col-lg-6 p-0">
                <div class="hovereffect">
                    <img class="img-fluid w-100 h-100" src="../assets/events.jpg" alt="">
                    <div class="overlay">
                        <h2 class="text-center" style="font-size:5vw;">SOCIAL <strong style="font-size:5vw;" class="text-warning display-2 font-weight-bold" s>MEDIA</strong></h2>
                        <p>
                            <a href="#">
                                <i class="fab fa-twitter" style="font-size: 3.4vw"></i>
                            </a>
                            <a href="#">
                                <i class="fab fa-facebook" style="font-size: 3.4vw"></i>
                            </a>
                            <a href="#">
                                <i class="fab fa-instagram" style="font-size: 3.4vw"></i>
                            </a>
                            <a href="#">
                                <i class="fab fa-youtube" style="font-size: 3.4vw"></i>
                            </a>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import { mdbIcon } from 'mdbvue';
    export default {
        name: "ContactBM",
        components: {
            mdbIcon,
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
    }

    .hovereffect img {
        display: block;
        position: relative;
    }

    .hovereffect h2 {
        text-transform: uppercase;
        color: #fff;
        text-align: center;
        font-size: 17px;
    }

    .hovereffect:hover h2 {
        opacity: 0;
        filter: alpha(opacity=0);
        -webkit-transform: translate3d(-50%,-50%,0) scale3d(0.8,0.8,1);
        transform: translate3d(-50%,-50%,0) scale3d(0.8,0.8,1);
    }

    .hovereffect a.info {
        display: inline-block;
        text-decoration: none;
        padding: 7px 14px;
        text-transform: uppercase;
        color: #fff;
        border: 1px solid #fff;
        margin: 50px 0 0 0;
        background-color: transparent;
    }

    .hovereffect a.info:hover {
        box-shadow: 0 0 5px #fff;
    }

    .hovereffect h2,
    .hovereffect p {
        position: absolute;
        top: 50%;
        left: 50%;
        -webkit-transition: opacity 0.35s, -webkit-transform 0.35s;
        transition: opacity 0.35s, transform 0.35s;
        -webkit-transform: translate3d(-50%,-50%,0);
        transform: translate3d(-50%,-50%,0);
        -webkit-transform-origin: 50%;
        -ms-transform-origin: 50%;
        transform-origin: 50%;
        background-color: transparent;
        margin: 0px;
        padding: 0px;
    }

    .hovereffect .overlay:before {
        position: absolute;
        top: 50%;
        left: 50%;
        width: 40%;
        height: 60%;
        border: 2px solid #fff;
        content: '';
        opacity: 0;
        filter: alpha(opacity=0);
        -webkit-transition: opacity 0.35s, -webkit-transform 0.35s;
        transition: opacity 0.35s, transform 0.35s;
        -webkit-transform: translate3d(-50%,-50%,0) rotate3d(0,0,1,-45deg) scale3d(0,0,1);
        transform: translate3d(-50%,-50%,0) rotate3d(0,0,1,-45deg) scale3d(0,0,1);
        -webkit-transform-origin: 50%;
        -ms-transform-origin: 50%;
        transform-origin: 50%;
    }

    .hovereffect p {
        width: 20%;
        text-transform: none;
        font-size: 15px;
        line-height: 2;
    }

    .hovereffect p a {
        color: #fff;
    }

    .hovereffect p a:hover,
    .hovereffect p a:focus {
        opacity: 0.6;
        filter: alpha(opacity=60);
    }

    .hovereffect  a i {
        opacity: 0;
        filter: alpha(opacity=0);
        -webkit-transition: opacity 0.35s, -webkit-transform 0.35s;
        transition: opacity 0.35s, transform 0.35s;
        padding: 0px 5px;
    }

    .hovereffect p a:first-child i {
        -webkit-transform: translate3d(-60px,-60px,0);
        transform: translate3d(-60px,-60px,0);
    }

    .hovereffect p a:nth-child(2) i {
        -webkit-transform: translate3d(60px,-60px,0);
        transform: translate3d(60px,-60px,0);
    }

    .hovereffect p a:nth-child(3) i {
        -webkit-transform: translate3d(-60px,60px,0);
        transform: translate3d(-60px,60px,0);
    }

    .hovereffect p a:nth-child(4) i {
        -webkit-transform: translate3d(60px,60px,0);
        transform: translate3d(60px,60px,0);
    }

    .hovereffect:hover .overlay:before {
        opacity: 1;
        filter: alpha(opacity=100);
        background-color: rgba(0,0,0,0.2);
        border-color: #dca90a;
        -webkit-transform: translate3d(-50%,-50%,0) rotate3d(0,0,1,-135deg) scale3d(1,1,1);
        transform: translate3d(-50%,-50%,0) rotate3d(0,0,1,-136.5deg) scale3d(1.4,1,1);
    }

    .hovereffect:hover p i:empty {
        -webkit-transform: translate3d(0,0,0);
        transform: translate3d(0,0,0);
        opacity: 1;
        filter: alpha(opacity=100);
    }

    /** textarea **/
    .noresize {
        resize: none;
    }
</style>
