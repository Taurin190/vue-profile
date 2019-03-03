<template>
  <div class="hoge">
      <Overview />
      Top Hoge
      <AppFooter />
  </div>
</template>
<script>
import Overview from '@/components/Overview.vue'
import AppFooter from '@/components/AppFooter.vue'

export default {
    name: "top",
    components: {
        Overview,
        AppFooter
    }
}
</script>


<style>
div .hoge {
    background-image: url(../assets/img/background-library.jpg);
}
</style>

