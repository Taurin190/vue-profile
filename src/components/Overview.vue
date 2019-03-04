<template>
<div id="overviewContainer">
  <div id="overviewHeader" class="clearfix">
    <div id="photoContainer" class="float-lg-right mx-auto">
        <img class="img-thumbnail" src="../assets/img/computer_hacker_black1.png"/>
    </div>
    <div id="profileOutlineContainer" class="float-lg-left w-lg-75">
        <h1 class="text-left">
          <span>あああああああ</span>
        </h1>
        <div id="introduction" class="text-left">
            私はこれこれこのようああああああああああああああああああああああああああああああああああああああああ
        </div>
        <div class="contentPanel">
          <div>
            <h3>プロフィール</h3>
          </div>
          <div>
            <div class="engagementInfo-line">
              <div class="engagementInfo-content engagementInfo-content js-countType clearfix" data-type="visits">
                <span class="engagementInfo-param">生年月日</span>
                <span class="engagementInfo-value">
              <span class="engagementInfo-valueNumber js-countValue">1986年5月1日（32歳）</span>
                </span>
              </div>
            </div>
            <div class="engagementInfo-line">
              <div class="engagementInfo-content engagementInfo-content js-countType clearfix" data-type="visits">
                <span class="engagementInfo-param">出身地</span>
                <span class="engagementInfo-value">
              <span class="engagementInfo-valueNumber js-countValue">日本</span>
                </span>
              </div>
            </div>
          </div>
        </div>
    </div>
  </div>
</div>
</template>
<script>
export default {
    name: "Overview"
}
</script>
<style>
h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: 700;
  font-family: 'Montserrat', 'Helvetica Neue', Helvetica, Arial, sans-serif;
}
@media (min-width: 992px) {
  .w-lg-75 {
    width: 75%;
  }
}
#photoContainer {
  width: 200px;
  padding-bottom: 15px;
}
#introduction {
  padding-bottom: 20px;
}
.contentPanel {
  margin: 5px 0 30px;
}

.engagementInfo-line {
  padding: 4px 0;
  border-bottom: #ededed 2px solid;
}

.engagementInfo-param {
  float: left;
}
.engagementInfo-value {
  float: right;
  display: inline-block;
  vertical-align: middle;
  width: 228px;
  margin-left: -2px;
  text-align: right;
  color: #096898;
  font-family: "Open Sans", sans-serif;
  font-weight: 600;
}

.engagementInfo-content {
  /* margin-right: 238px; */
  height: 2.5em;
  line-height: 2.5em;
  white-space: nowrap;
  transition: margin-right 300ms ease;
  font-size: 16px;
  font-size: 1rem;
}

</style>


