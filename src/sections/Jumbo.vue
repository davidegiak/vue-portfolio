<script>
import store from '../data/store.js';

export default {
    name: 'Jumbo',
    data() {
        return {
            store,
        }
    }
}
</script>

<template>
    <div class="jumbo d-flex justify-content-between align-items-center ">
        <div class="col-3 col-md-4 col-lg-5 mx-auto text-center text-shadow">
            <h2 class="jumboDesc mx-auto text-light">Sono <span class="DynaPuff text-warning">Davide Di Giacomo</span> e sono un
                <span class="DynaPuff text-warning">Programmatore.</span>
            </h2>
        </div>
        <div class="col-8 col-sm-6 col-md-5 col-lg-5">
            <img class="jumboImg" src="/src/assets/fotoCurriculumNuova-removebg-preview.png" style="">

        </div>
    </div>
</template>

<style scoped>
.jumboImg {
    width: 100%;
    filter: grayscale(100%)
}
.jumbo {
    background-color: #34353a;
}
.jumboDesc{
    font-size: 2.5rem;
}
@media screen  and (max-width: 768px) {
    .jumboDesc{
        font-size: 1.3rem;
    }
}
</style>