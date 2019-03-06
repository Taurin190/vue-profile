<template>
  <div id="accountContainer" class="contentContainer">
    <h2 class="text-left">アカウント</h2>
    <div class="row">
      <div class="col-lg-5 col-lg-push-7 contentContainer">
        <h3 class="text-left">Twitter情報</h3>
        <div class="engagementInfo-line">
          <div class="engagementInfo-content">
            <span class="engagementInfo-param">ツイート</span>
            <span class="engagementInfo-value">1,222</span>
          </div>
        </div>
        <div class="engagementInfo-line">
          <div class="engagementInfo-content">
            <span class="engagementInfo-param">フォロー</span>
            <span class="engagementInfo-value">270</span>
          </div>
        </div>
        <div class="engagementInfo-line">
          <div class="engagementInfo-content">
            <span class="engagementInfo-param">フォロワー</span>
            <span class="engagementInfo-value">170</span>
          </div>
        </div>
        <div class="engagementInfo-line">
          <div class="engagementInfo-content">
            <span class="engagementInfo-param">いいね</span>
            <span class="engagementInfo-value">1</span>
          </div>
        </div>
      </div>
      <div class="col-lg-7 col-lg-pull-5">
        <div id="chart_div"></div>
      </div>
    </div>
    <div class="row">
      <div class="col-lg-6 contentContainer">
        <h3 class="text-left">ツイートの話題</h3>
        <div class="engagementInfo-line">
          <div class="engagementInfo-content">
            <span class="engagementInfo-param">エンジニアリング</span>
            <span class="engagementInfo-value">35%</span>
          </div>
        </div>
        <div class="engagementInfo-line">
          <div class="engagementInfo-content">
            <span class="engagementInfo-param">プログラム</span>
            <span class="engagementInfo-value">17%</span>
          </div>
        </div>
        <div class="engagementInfo-line">
          <div class="engagementInfo-content">
            <span class="engagementInfo-param">サッカー</span>
            <span class="engagementInfo-value">10%</span>
          </div>
        </div>
        <div class="engagementInfo-line">
          <div class="engagementInfo-content">
            <span class="engagementInfo-param">その他</span>
            <span class="engagementInfo-value">8%</span>
          </div>
        </div>
      </div>
      <div class="col-lg-6">
        <div id="piechart"></div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name: 'Account'
}
</script>

<style>

</style>


