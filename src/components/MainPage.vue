<template>
  <div>
    <div class="first">
        <div class="left">
            <div class="container">
                <h1 class="text-uppercase title">every moment counts</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis mollitia porro inventore adipisci maiores. Nam consequatur earum ea corporis reprehenderit, quisquam explicabo magnam sapiente exercitationem nobis autem recusandae rerum error.</p>
                <button class="btn text-uppercase">our mission</button>
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
                <h1>3.8 M</h1>
                <p class="text-white">Donated</p>
            </div>
        </div>
    </div>

    <div class="second">
        <div class="second-title">
            <h1 class="text-uppercase text-white values-title">our values</h1>
            <p class="text-white">Think Big. Act Bigger.</p>
        </div>
        <div class="second-container">
            <div class="row row-cols-4">
                <div class="col second-card">
                    <h3 class="text-white">Clean Water</h3>
                    <p class="text-white">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                    <button class="btn text-uppercase">learn more</button>
                </div>
                <div class="col second-card">
                    <h3 class="text-white">Vaccinations</h3>
                    <p class="text-white">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                    <button class="btn text-uppercase">learn more</button>
                </div>
                <div class="col second-card">
                    <h3 class="text-white">Education</h3>
                    <p class="text-white">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                    <button class="btn text-uppercase">learn more</button>
                </div>
                <div class="col second-card">
                    <h3 class="text-white">Farming</h3>
                    <p class="text-white">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                    <button class="btn text-uppercase">learn more</button>
                </div>
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

.btn {
    background-color: #FCD66C;
    color: white;
    border-radius: 0;
}

.btn:hover {
    background-color: #ca9e26;
    transition: .5s;
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

.second {
    background-image: url('@/img/home-content-bg-2.jpg');
    background-position: center;
    width: 100%;
    height: 600px;
    padding: 5rem;
}

.second-container {
    margin-top: 5rem;
}

.second-title {
    text-align: center;
    display: flex;
    flex-direction: column;
    gap: .5rem;
    position: relative;
}

.values-title::after {
    background-color: #FCD66C;
    bottom: 0;
    content: '';
    display: block;
    height: 2px;
    left: 50%;
    position: absolute;
    transform: translate(-50%, 0);
    width: 100px;
}

.second-card {
    text-align: center;
    display: flex;
    flex-direction: column;
    gap: .5rem;
}

.second-card .btn {
    width: max-content;
    margin: 0 auto;
}
</style>