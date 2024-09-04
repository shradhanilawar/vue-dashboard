<template>
    <section class="mt-5">
        <div class="row d-flex justify-content-center">
            <button class="view-all">View All</button>
            <p class="text-center latest-api mt-3">
                <span>
                    Upcoming Event
                </span>
            </p>
        </div>
        <div class="row slider">
            <div class="col-3 slider-img mt-3 mb-3">
                <img src="../assets/pexels.png" alt="">
            </div>
            <div class="col-9 mt-3 mb-3">
                <h5>API Consumption</h5>
                <h6>Lorem Ipsum Dolor Sit Amet, Consectetur Adipiscing Lorem Ipsum Dolor Sit Amet Dolor Sit A Lorem
                    Ipsum
                    Dolor Sit Amet, Consectetur Adipiscing Lorem Ipsum Dolor Sit Amet Dolor Sit A</h6>

                <button type="button" class="btn btn-outline-secondary mt-5">Read more</button>
            </div>

        </div>
    </section>
</template>
<style scoped>
h5 {
    text-align: left;
    font: normal normal bold 22px/27px Calibri;
    letter-spacing: 0px;
    color: #242424;
}

h6 {
    text-align: left;
    font: normal normal 300 18px/22px Calibri;
    letter-spacing: 0px;
    color: #242424;
}

.view-all {
    width: 174px !important;
    height: 60px;
    /* UI Properties */
    background: #27DEBF 0% 0% no-repeat padding-box;
    border-radius: 5px;
    border-color: #27DEBF
}

.slider {
    height: max-content;
    /* UI Properties */
    background: #FFFFFF 0% 0% no-repeat padding-box;
    box-shadow: 0px 15px 20px #7682B72D;
    border-radius: 5px;
}
</style>