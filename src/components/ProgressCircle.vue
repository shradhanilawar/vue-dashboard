<template>
    <section>
        <div class="row d-flex justify-content-between">
            <div class="col-3 circle d-flex align-items-center justify-content-center">
                <div class="inner-circle d-flex flex-column justify-content-center align-items-center">
                    <h1>50%</h1>
                    <p>API</p>
                </div>
            </div>
            <div class="col-3 circle d-flex align-items-center justify-content-center">
                <div class="inner-circle d-flex flex-column justify-content-center align-items-center">
                    <h1>75%</h1>
                    <p>Reusable API</p>
                </div>
            </div>
            <div class="col-3 circle d-flex align-items-center justify-content-center">
                <div class="inner-circle d-flex flex-column justify-content-center align-items-center">
                    <h1>20%</h1>
                    <p>Reusable API</p>
                </div>
            </div>
            <div class="col-3 circle d-flex align-items-center justify-content-center">
                <div class="inner-circle d-flex flex-column justify-content-center align-items-center">
                    <h1>50%</h1>
                    <p>Reusable API</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.inner-circle {
    height: 150px;
    width: 150px;
    border-radius: 50%;
    border: 3px solid #27DEBF;
}

.circle {
    height: 180px;
    width: 180px;
    border-radius: 50%;
    background-color: white !important;
    box-shadow: 0px 15px 20px #151D410F;
}

h1 {
    font: normal normal bold 36px/44px Calibri;
    letter-spacing: 0px;
    color: #151D41;
}

p {
    font: normal normal 300 20px/32px Calibri;
    letter-spacing: 0px;
    color: #151D41;
}
</style>