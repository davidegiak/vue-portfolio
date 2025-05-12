<template>
    <div class="contatti position-fixed d-flex flex-column p-3 gap-2">
        <a href="" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-instagram text-warning"></i></a>
        <a href="" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-linkedin-in text-warning"></i></a>
        <a href="" target="_blank" rel="noopener noreferrer"><i class="fa-solid fa-envelope text-warning"></i></a>
        <a href="" target="_blank" rel="noopener noreferrer"><i class="fa-brands fa-github text-warning"></i></a>
    </div>
</template>

<style lang="scss" scoped>
.contatti {
    z-index: 99999;
    font-size: 2rem;
    right: 0;
    top: 10rem;
}
a:hover {
    color: white;

}

@media screen and (max-width: 600px) {
    .contatti {
        font-size: 2.5rem;
        right: 0;
        top: 10rem;
    }
}
</style>