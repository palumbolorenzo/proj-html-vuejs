<template>
  <div>
    <div class="first">
        <div class="first-title-cont">
            <div class="first-title">
                <h2 class="text-uppercase title text-white">change a life today</h2>
            </div>

            <div class="subtitle text-white">
                <p class="">As long as poverty, injustice & inequality persist, none of us can truly rest. It doesn't take much to change a life. Het in touch today and start making the difference.</p>
            </div>

            <div class="buttons">
                <button class="btn text-uppercase">volunteer</button>
                <button class="btn text-uppercase">donate now</button>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
name: 'FooterPage'
}
</script>

<style lang="scss" scoped>
.first {
    background-image: url('@/img/home-footer.jpg');
    height: 550px;
    background-position: center;
}

.title {
    text-align: center;
    display: flex;
    flex-direction: column;
    gap: 1rem;
    position: relative;
}

.first-title-cont {
    padding: 10rem 10rem 5rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
}

.title::after {
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

.buttons {
    display: flex;
    justify-content: center;
    gap: 1rem;
}

.btn {
    border: 1px solid white;
    color: white;
    border-radius: 0;
    padding: .5rem 1rem;
}

.btn:hover {
    border: 1px solid #FCD66C;
    color: #FCD66C;
    transition: .5s;
}
</style>