<template>
    <div>
        <div class="blue">
            <ul class="cards">
                <li class="card">
                    <img src="@/img/buy-comics-digital-comics.png" alt="">
                    <p class="card-text">digital comics</p>
                </li>
                <li class="card">
                    <img src="@/img/buy-comics-merchandise.png" alt="">
                    <p class="card-text">dc merchandise</p>
                </li>
                <li class="card">
                    <img src="@/img/buy-comics-subscriptions.png" alt="">
                    <p class="card-text">subscription</p>
                </li>
                <li class="card">
                    <img src="@/img/buy-comics-shop-locator.png" alt="">
                    <p class="card-text">subscription</p>
                </li>
                <li class="card">
                    <img src="@/img/buy-dc-power-visa.svg" alt="">
                    <p class="card-text">dc power visa</p>
                </li>
            </ul>
        </div>    
    </div>
</template>

<script>
export default {
    name: 'SectionBlue',
}
</script>

<style lang="scss" scoped>
.blue {
    background-color: #0282F9;
    height: 155px;
    display: flex;
    justify-content: center;
}

img {
    width: 50px;
}

.cards {
    padding: 0 ;
    display: flex;
    gap: 2rem;
}

.card {
    display: flex;
    align-items: center;
    gap: .5rem;
}

.card-text {
    white-space: nowrap;
    color: white;
    text-transform: uppercase;
}
</style>