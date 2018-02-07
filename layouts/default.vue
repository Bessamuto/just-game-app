<template>
    <div>
        <app-header></app-header>
        <div class="content">
            <nuxt/>
        </div>
    </div>
</template>
<script>
  import appHeader from '~/components/header/header'

  export default {
    components: {
      'app-header': appHeader
    }
  }
</script>
<style lang="scss">
    @import "../assets/scss/app.scss";
</style>