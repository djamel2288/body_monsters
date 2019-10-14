<template>
    <mdb-card>
        <div class="row">
            <div class="col-6">
                <img src="../assets/events.jpg" class="card-img w-100" alt="..." style="min-height: 200px;">
            </div>
            <mdb-card-body class="col-6">
                <h1 class="card-title">
                    Basic Card
                </h1>
                <p class="card-text">
                    Some quick example text to build on the card title and make up the bulk of the card's content.
                </p>
                <mdb-btn color="warning ">Button</mdb-btn>
            </mdb-card-body>
        </div>
    </mdb-card>
</template>

<script>
    import { mdbCard, mdbCardImage, mdbCardBody, mdbCardTitle, mdbCardText, mdbBtn } from 'mdbvue';
    export default {
        name: "BmEvents",
        components: {
            mdbCard,
            mdbCardImage,
            mdbCardBody,
            mdbCardTitle,
            mdbCardText,
            mdbBtn
        }
    }
</script>

<style scoped>

</style>
