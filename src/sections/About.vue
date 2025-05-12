<script>
import store from '../data/store.js'
import TechCards from './TechCards.vue';

export default {
    name: 'About',
    components: { TechCards },
    data() {
        return {
            store,
        }
    },
}
</script>
<template>
    <div class="back">
        <div class="container px-5 d-md-px-0">
            <div class="gradino"></div>
            <div class="row">
                <h1 class="text-light my-4 young-serif text-shadow"><span class="text-warning young-serif">CHI S</span>ONO</h1>
            </div>
            <div class="row">
                <div class="riga bg-warning col-1"></div>
                <div class="col-10 fs-5 text-light text-shadow">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat earum animi ea nulla vel suscipit
                        cumque accusamus, asperiores rem, vitae veniam repudiandae! Necessitatibus adipisci iure, nisi natus
                        atque tempora vero!
                        In architecto labore soluta nihil asperiores et officiis ab consequatur illo non consequuntur
                        voluptatibus porro, at sapiente blanditiis earum enim deserunt commodi quia. Dolores numquam,
                        veritatis magnam dolor cum laborum.</p>
                </div>
            </div>
            <div class="row mt-5">
                <h1 class="text-light text-center mt-5 mb-5 young-serif text-shadow">SK<span class="text-warning young-serif">ILL</span>S</h1>
            </div>
            <div class="row gap-4 justify-content-center py-3">
                <TechCards class="col-5 col-md-3 col-lg-2" v-for="item, index in store.tech" :key="index" :techs="item" />
            </div>
        </div>
    </div>
</template>
<style scoped>
.riga {
    height: 2px;
    margin-top: 15px;
}
.back{
    background-color: #31333b;
    border-top: 5px solid rgba(0, 0, 0, 0.053);
}
</style>