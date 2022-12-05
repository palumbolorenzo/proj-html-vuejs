<template>
  <div>
    <div class="first">
        <div class="left">
            <div class="container">
                <h1 class="text-uppercase title">every moment counts</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis mollitia porro inventore adipisci maiores. Nam consequatur earum ea corporis reprehenderit, quisquam explicabo magnam sapiente exercitationem nobis autem recusandae rerum error.</p>
            </div>
        </div>
        <div class="right">
            <div class="text1 text-white">
                <h1>2032</h1>
                <p class="text-white">Volunteers worldwide</p>
            </div>
            <div class="text2 text-white">
                <h1>132</h1>
                <p class="text-white">Active projects</p>
            </div>
            <div class="text3 text-white">
                <h1>3.8M</h1>
                <p class="text-white">Donated</p>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
name: 'MainPage',
}
</script>

<style lang="scss" scoped>
.first {
    display: flex;
}

.left {
    padding: 3rem;
    display: flex;
    flex-direction: column;
    flex-basis: 60%;
}

.title {
    border-bottom: 3px solid #FCD66C;
    margin-bottom: 2rem;
}

.right {
    background-image: url('@/img/home-content-bg-1.jpg');
    background-position-x: bottom;
    background-position-y: center;
    height: 500px;
    display: flex;
    flex-basis: 40%;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    gap: 2rem;
}

.text1, .text2, .text3 {
    display: flex;
    flex-direction: column;
    align-items: center;
}
</style>