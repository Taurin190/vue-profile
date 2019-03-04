<template>
  <nav class="scroll-navbar scroll-nav js-scroll-nav is-fixed" role="navigation">
    <a class="navigationLink with-icon js-scroll-trigger overview fa fa-chart-bar js-navigationLink is-active" data-section="overview" href="#overviewContainer">概要</a>
    <a class="navigationLink with-icon js-scroll-trigger account fa fa-user-circle disabledInCompared js-navigationLink" data-section="referrals" href="#accountContainer">公式アカウント</a>
    <a class="navigationLink with-icon js-scroll-trigger audience fa fa-comments disabledInCompared js-navigationLink" data-analytics-category="Scroll Link" data-analytics-label="Navigation Bar/Search" data-section="search" href="#audienceContainer">オーディエンス</a>
    <a class="navigationLink with-icon js-scroll-trigger personality fa fa-heart icon-personality disabledInCompared js-navigationLink" data-section="social" href="javascript:void(0)">人物像</a>
    <a class="navigationLink with-icon js-scroll-trigger related-people fa fa-users disabledInCompared js-navigationLink" data-section="display" href="javascript:void(0)">関連人物</a>
    <a class="navigationLink with-icon js-scroll-trigger oeuvre fa fa-book disabledInCompared js-navigationLink" data-section="websiteContent" href="javascript:void(0)">著書・出演</a>
    <a class="navigationLink with-icon js-scroll-trigger related-links fa fa-link disabledInCompared js-navigationLink" data-section="alsoVisited" href="javascript:void(0)">関連リンク</a>
  </nav>
</template>

<script>
export default {
    name: "AppSidebar"
}
</script>
<style>
.scroll-navbar.is-fixed {
  position: fixed;
  top: 110px;
}

.scroll-navbar {
  width: 90px;
  margin-left: -90px;
  z-index: 104;
  text-align: center;
}

nav {
  display: block;
}

a.navigationLink {
  display: block;
  position: relative;
  margin-bottom: 0.5em;
  z-index: 10;
  padding-right: 5px;
  color: #d8d8d8;
  line-height: 1em;
  text-transform: capitalize;
  font-size: 14px;
  font-size: .875rem;
}

a.navigationLink.with-icon::before {
  display: block;
  line-height: 1.4;
  font-size: 26px;
  font-size: 1.625rem
}

@media (max-width: 992px) {
  .scroll-nav {
    display: none;
  }
}

.navigationLink.account:hover,
.navigationLink.account.is-active {
  color: #bd8ed0
}

.navigationLink.audience:hover,
.navigationLink.audience.is-active {
  color: #f60
}

.navigationLink.personality:hover,
.navigationLink.personality.is-active {
  color: #00b5f0
}

.navigationLink.related-links:hover,
.navigationLink.related-links.is-active {
  color: #ccb5f0
}

.navigationLink.related-people:hover,
.navigationLink.related-people.is-active {
  color: #ff24c7
}

.navigationLink.oeuvre:hover,
.navigationLink.oeuvre.is-active {
  color: #2fc5cc
}

.navigationLink.alsoVisited:hover,
.navigationLink.alsoVisited.is-active {
  color: #96f
}

.navigationLink.overview:hover,
.navigationLink.overview.is-active {
  color: #00b5f0;
}

</style>
