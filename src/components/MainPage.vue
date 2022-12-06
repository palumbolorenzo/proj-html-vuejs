<template>
  <div>
    <div class="first">
        <div class="left">
            <div class="container">
                <h2 class="text-uppercase title">every moment counts</h2>
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
            <h2 class="text-uppercase text-white values-title">our values</h2>
        </div>

        <div class="subtitle">
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

    <div class="third">
        <div class="third-title">
            <h2 class="text-uppercase causes-title">recent causes</h2>
        </div>

        <div class="subtitle">
            <p class="">We run projects in over 30 countries in 5 continents</p>
        </div>

        <div class="pics-container">
            <div class="row row-cols-4">
                <div class="col">
                    <img src="@/img/avada-charity-fair-trade-featured-600x450.jpg" class="hover">
                </div>
                <div class="col">
                    <img src="@/img/avada-charity-shelter-featured-600x450.jpg" class="hover">
                </div>
                <div class="col">
                    <img src="@/img/avada-charity-farming-featured-600x450.jpg" class="hover">
                </div>
                <div class="col">
                    <img src="@/img/avada-charity-vaccines-featured-600x450.jpg" class="hover">
                </div>
            </div>
        </div>
    </div>

    <div class="fourth">
        <div>
            <p class="text-uppercase text-white central">view all our causes</p>
        </div>
    </div>

    <div class="fifth">
        <div class="fifth-container row row-cols-2">
            <div class="fifth-left col">
                <div class="big-pic">
                    <img src="@/img/photo-1444213007800-cff19e1677ac-600x450.jpg" alt="">
                </div>
                <div class="description">
                    <div class="contact-desc">
                        <h6>The human story of uniqueness</h6>
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Prasent ac nibh vestibulum, laoreet ipsum.</p>
                    </div>
                </div>
            </div>

            <div class="fifth-right col">
                <div class="contacts">
                    <div class="contact">
                        <img src="@/img/photo-1444664597500-035db93e2323-177x142.jpg" class="img-fluid">
                        <div class="contact-desc">
                            <h6>The human story of uniqueness</h6>
                            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Prasent ac nibh vestibulum, laoreet ipsum.</p>
                        </div>
                    </div>
                    <div class="contact">
                        <img src="@/img/photo-1447430617419-95715602278e-177x142.jpg" class="img-fluid">
                        <div class="contact-desc">
                            <h6>Sustainable trade tactics</h6>
                            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Prasent ac nibh vestibulum, laoreet ipsum.</p>
                        </div>
                    </div>
                    <div class="contact">
                        <img src="@/img/photo-1460230525622-630fe3294cd7-177x142.jpg" class="img-fluid">
                        <div class="contact-desc">
                            <h6>Farmers making a difference</h6>
                            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Prasent ac nibh vestibulum, laoreet ipsum.</p>
                        </div>
                    </div>
                    <div class="contact">
                        <img src="@/img/photo-1460600421604-5e138c208b9c-177x142.jpg" class="img-fluid">
                        <div class="contact-desc">
                            <h6>Meeting remote tribes in Peru</h6>
                            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Prasent ac nibh vestibulum, laoreet ipsum.</p>
                        </div>
                    </div>
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
    color: white;
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

.second-title, .third-title {
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
    width: 150px;
}

.causes-title::after {
    background-color: #FCD66C;
    bottom: 0;
    content: '';
    display: block;
    height: 2px;
    left: 50%;
    position: absolute;
    transform: translate(-50%, 0);
    width: 170px;
}

.subtitle {
    margin-top: 1rem;
    text-align: center;
    display: flex;
    flex-direction: column;
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

.third {
    padding: 5rem;
}

.pics-container {
    margin-top: 3rem;
}

.hover:hover {
    transform: scale(1.05);
    filter: brightness(75%);
    transition: 1s;
    cursor: pointer;
}

.fourth {
    background-color: #ED6864;
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.fifth-container {
    padding: 5rem;
    display: flex;
    justify-content: center;
}

.description {
    padding: 1rem;
    border: 1px solid #EBEAEA;
}

.contacts {
    display: flex;
    flex-direction: column;
    gap: 2rem;
}

.contact {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.contact img {
    width: 150px;
}

.contact-desc h6 {
    color: #FCD66C;
}
</style>