<template>
  <div class="bg-container">
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
    display: flex;
    align-items: center;
    justify-content: center;
}

.title {
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