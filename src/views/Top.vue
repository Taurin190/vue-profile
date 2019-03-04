<template>
  <div class="container">
    <div>
      <AppSidebar />
      <div id="mainContainer">
        <Overview />
        Top Hoge
      </div>
    </div>
    <AppFooter />
  </div>
</template>
<script>
import Overview from '@/components/Overview.vue'
import AppSidebar from '@/components/AppSidebar.vue'
import AppFooter from '@/components/AppFooter.vue'

export default {
    name: "top",
    components: {
        Overview,
        AppSidebar,
        AppFooter
    }
}
</script>

<style>
#mainContainer {
  margin-top: 80px;
  padding: 15px;
  background-color: #ffffff;
  border: #c7c7c7 1px solid;
  border-bottom: none;
  box-shadow: 3px 3px 5px 0 rgba(0, 0, 0, 0.05);
}
</style>

