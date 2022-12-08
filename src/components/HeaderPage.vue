<template>
  <div class="bg-container">
    <div class="header">
      <div>
        <img
          src="@/img/avada-charity-sticky-header-logo.png"
          class="logo"
        >
      </div>

      <ul class="links">
        <li
          v-for="objLink in arrLinks"
          :key="objLink"
          class="text-uppercase link"
        >
          {{ objLink.link }}
        </li>
        <li>
          <a
            href="#!"
            class="upper-btn text-uppercase"
          >
            donate
          </a>
        </li>
      </ul>
    </div>
    <div class="title">
      <h1 class="text-uppercase text-white">
        Make a difference
      </h1>
      <p class="text-white">
        As long as poverty, injustice & inequality persist, none of us can truly rest
      </p>
      <div class="buttons">
        <button class="btn text-uppercase">
          our mission
        </button>
        <button class="btn text-uppercase">
          donate now
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: 'HeaderPage',

data() {
    return {
        arrLinks: [
            {
                link: 'home'
            },
            {
                link: 'mission'
            },
            {
                link: 'causes'
            },
            {
                link: 'journal'
            },
        ]
    }
}
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

.links {
    display: flex;
    align-items: center;
    gap: 3rem;
}

li {
    list-style-type: none;
    color: white;
}

.link:hover {
    color: #FCD66C;
    border-bottom: 2px solid #FCD66C;
    cursor: pointer;
    transform: scale(1.1);
    transition: .5s;
}

.upper-btn {
    text-decoration: none;
    color: white;
    background-color: #FCD66C;
    padding: .4rem 1rem;
}

.upper-btn:hover {
    background-color: #ca9e26;
    transition: .5s;
}
</style>