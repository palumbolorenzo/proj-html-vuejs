<template>
  <div>
    <div class="first">
      <div class="first-title-cont">
        <div class="first-title">
          <h2 class="text-uppercase change-title text-white">
            change a life today
          </h2>
        </div>

        <div class="subtitle text-white">
          <p class="">
            As long as poverty, injustice & inequality persist, none of us can truly rest. It doesn't take much to change a life. Het in touch today and start making the difference.
          </p>
        </div>

        <div class="buttons">
          <button class="btn text-uppercase">
            volunteer
          </button>
          <button class="btn text-uppercase">
            donate now
          </button>
        </div>
      </div>
    </div>

    <div class="second">
      <div class="logo-container">
        <img
          src="@/img/avada-charity-mobile-logo-retina.png"
          class="logo"
        >
      </div>
    </div>

    <div class="third">
      <div class="info-container">
        <ul class="info">
          <li
            v-for="objInfo in arrInfo"
            :key="objInfo"
            class="text-uppercase link"
          >
            {{ objInfo.info }}
          </li>
        </ul>
      </div>
      <div class="socials">
        <font-awesome-icon
          icon="fa-brands fa-facebook"
          class="social"
        />
        <font-awesome-icon
          icon="fa-brands fa-instagram"
          class="social"
        />
        <font-awesome-icon
          icon="fa-brands fa-twitter"
          class="social"
        />
        <font-awesome-icon
          icon="fa-brands fa-youtube"
          class="social"
        />
      </div>
      <button
        class="top"
        @click="toTop"
      >
        <font-awesome-icon icon="fa-solid fa-chevron-up" />
      </button>
    </div>
  </div>
</template>

<script>

export default {
name: 'FooterPage',
data() {
    return {
        arrInfo: [
            {
                info: 'Copyright 2012 - 2020 AVADA THEME BY THEME FUSION'
            },

            {
                info: 'ALL RIGHTS RESERVED'
            },

            {
                info: 'POWERED BY WORDPRESS'
            },
        ]
    }
},
mounted() {
    window.addEventListener('scroll', this.handlescroll);
},
methods: {
    toTop: function () {
        window.scrollTo({
            top: 0,
            behavior: "smooth"
        });
    }
}
}
</script>

<style lang="scss" scoped>
.first {
    background-image: url('@/img/home-footer.jpg');
    height: 550px;
    background-position: center;
}

.change-title {
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

.change-title::after {
    background-color: #FCD66C;
    bottom: -20px;
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

.second {
    padding: 2rem;
    height: auto;
    display: flex;
    justify-content: center;
}
.logo:hover {
    transform: scale(1.025);
    transition: .5s;
    cursor: pointer;
}

.third {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    gap: 1rem;
    background-color: #F5F5F5;
    padding: 2rem;
    position: relative;
}

.info {
    display: flex;
    color: #DADBDB;
}

.socials {
    display: flex;
    gap: 1rem;
}

.social {
    background-color: #FFFFFF;
    color: #FCD66C;
    height: 20px;
    padding: .5rem;
    border-radius: 20rem;
}

.social:hover {
    transform: scale(1.25);
    transition: .5s;
    cursor: pointer;
}

li {
    list-style-type: none;
}

.top {
    width: 50px;
    height: 50px;
    background-color: #464646;
    color: #DADBDB;
    position: absolute;
    bottom: 0;
    right: 3rem;
}

.top:hover {
    background-color: #DADBDB;
    color: #464646;
    transition: .5s;
}
</style>