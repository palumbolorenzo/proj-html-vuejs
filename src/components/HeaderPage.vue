<template>
  <div class="bg-container">
    <div class="header">
        <div>
            <img src="@/img/avada-charity-sticky-header-logo.png" class="logo">
        </div>
    </div>
    <div class="title">
        <h1 class="text-uppercase text-white">Make a difference</h1>
        <p class="text-white">As long as poverty, injustice & inequality persist, none of us can truly rest</p>
        <div class="buttons">
            <button class="btn text-uppercase">our mission</button>
            <button class="btn text-uppercase">donate now</button>
        </div>
    </div>
  </div>
</template>

<script>
export default {
name: 'HeaderPage',
}
</script>

<style lang="scss" scoped>
.bg-container {
    background-image: url('@/img/home-page-slider.jpg');
    background-position: center;
    height: 1000px;
    /*align-items: center;
    justify-content: center;
    flex-direction: column;*/
}

.header {
    padding: 2rem;
    display: flex;
    justify-content: space-between;
}

.logo {
    cursor: pointer;
}

.logo:hover {
    transform: scale(1.05);
    transition: 1s;
}

.title {
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: .8rem;
    height: calc(1000px - 250px);
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