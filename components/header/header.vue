<template>
    <div class="header">
        <div class="content row">
            <div class="nav row__item row__item--vm row__item--col-2">
                <div class="nav__item"><a href="" class="link link--no-decor">Lorem</a></div>
                <div class="nav__item"><a href="" class="link link--false">Ipsun</a></div>
                <div class="nav__item"><a href="" class="link">Dolor</a></div>
            </div>
            <div class="logo row__item row__item--vm row__item--col-6">
                <img src="~/static/logo.svg">
            </div>
            <div class="auth row__item row__item--vm row__item--col-2 text--right">
                <div class="nav">
                    <div class="nav__item"><a href="" class="link link--false">Sign In</a></div>
                    <div class="nav__item"><a href="" class="link link--false">Log In</a></div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
  export default {
    data () {
      return {
        auth: false
      }
    }
  }
</script>
<style scoped lang="scss">
    .logo {
        text-align: center;
        img {
            width: 60px;
            animation: 3s rotate infinite;
            animation-delay: 10s;
        }
    }
    @keyframes rotate {
        0% {
            transform: rotate(0deg);
        }
        20% {
            transform: rotate(30deg);
        }
        40% {
            transform: rotate(90deg);
        }
        60% {
            transform: rotate(0deg);
        }
    }
</style>