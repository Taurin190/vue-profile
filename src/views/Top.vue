<template>
  <main class="container">
    <div>
      <AppSidebar />
      <div id="mainContainer">
        <Overview />
        <Account />
      </div>
    </div>
  </main>
</template>
<script>
import Overview from '@/components/Overview.vue'
import Account from '@/components/Account.vue'
import AppSidebar from '@/components/AppSidebar.vue'
import AppFooter from '@/components/AppFooter.vue'

export default {
    name: "top",
    components: {
        Overview,
        Account,
        AppSidebar
    }
}
</script>

<style>
main {
  margin-top: 54px;
}
#mainContainer {
  margin-top: 80px;
  padding: 15px;
  background-color: #ffffff;
  border: #c7c7c7 1px solid;
  border-bottom: none;
  box-shadow: 3px 3px 5px 0 rgba(0, 0, 0, 0.05);
}
</style>

