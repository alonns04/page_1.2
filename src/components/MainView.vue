<script setup>
</script>

<template>
    <div>
        <div class="container-fluid">
            <div class="grid-container">
                <div class="grid-item1"></div>
                <div class="grid-item2"></div>
                <div class="grid-item3"></div>
                <div class="grid-item4"></div>
                <div class="grid-item5"></div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.grid-item1 {
    background-size: 100%;
    background-repeat: no-repeat;
    background-image: url(https://static-resources-elementor.mirai.com/wp-content/uploads/sites/346/Image-3.jpg);
    grid-area: area1;
}

.grid-item2 {
    background-size: 100%;
    background-repeat: no-repeat;
    background-image: url(https://www.hotelreginamadrid.com/wp-content/uploads/2022/02/00-habitacion-atico-hotel-regina.jpg);
    grid-area: area2;
}

.grid-item3 {
    background-size: 100%;
    background-repeat: no-repeat;
    background-image: url(https://granhotelnagari.com/wp-content/uploads/2022/04/habitacionesGSA.jpg);
    grid-area: area3;
}

.grid-item4 {
    background-size: 100%;
    background-repeat: no-repeat;
    background-image: url(https://lledogrupo.com/wp-content/uploads/2019/09/182.jpg);
    grid-area: area4;
}

.grid-item5 {
    background-size: 100%;
    background-repeat: no-repeat;
    background-image: url(https://granhotelnagari.com/wp-content/uploads/2022/04/slidersuitealameda05.jpg);
    grid-area: area5;
}

.grid-container {
    display: grid;
    grid-template-rows: 50px 70px 140px 70px 140px 70px 140px ;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-gap: 10px;
    grid-template-areas:
        ". . . ."
        ". .         area2 area2"
        "area1 area1 area2 area2"
        "area1 area1 area3 area3"
        "area4 area4 area3 area3"
        "area4 area4 area5 area5"
        ". .         area5 area5";
}

div {
    background-color: black;
}
</style>