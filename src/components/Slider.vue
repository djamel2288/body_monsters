<template>
    <div>
        <b-carousel
                id="carousel-1"
                v-model="slide"
                :interval="2000"
                controls
                indicators
                background="#ababab"
        >            <!-- Slides with img slot -->
            <!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->

            <b-carousel-slide
                    caption="First slide"
                    text="BodyMonsters-BodyMonsters-BodyMonsters-BodyMonsters-BodyMonsters-BodyMonsters">
                <template v-slot:img>
                    <img
                            style="max-height: 750px"
                            class="d-block img-fluid w-100"
                            src="../assets/bmg.png"
                            alt="image slot"
                    >
                    <!--div class="position">Black</div-->
                </template>
            </b-carousel-slide>

            <b-carousel-slide
                    caption="Second slide"
                    text="BodyMonsters-BodyMonsters-BodyMonsters-BodyMonsters-BodyMonsters-BodyMonsters">
                <template v-slot:img>
                    <img
                            style="max-height: 750px"
                            class="d-block img-fluid w-100"
                            src="../assets/bmb.png"
                            alt="image slot"
                    >
                    <!--div class="position">Black</div-->
                </template>
            </b-carousel-slide>

            <b-carousel-slide
                    caption="Third slide"
                    text="BodyMonsters-BodyMonsters-BodyMonsters-BodyMonsters-BodyMonsters-BodyMonsters"
            >
                <template v-slot:img>
                    <img
                            style="max-height: 750px"
                            class="d-block img-fluid w-100"
                            src="../assets/bodymonsters.jpg"
                            alt="image slot"
                    >
                    <!--div class="position">Black</div-->
                </template>
            </b-carousel-slide>


        </b-carousel>
    </div>
</template>

<script>
    export default {
        name: "Slider"
    }
</script>

<style scoped>
    .position {
        position: absolute;
        bottom: 10%;
        left: 50%;
        transform: translate(-50%, -50%);
        color: #dca90a;
        font-size: 4vmax;
    }
</style>

