---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 4
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>

<style>
  /* 1. 우측 사이드바(목차/스크롤스파이)의 연도 글씨 */
  nav[data-toggle="toc"] .nav-link, 
  .section-nav .toc-entry a {
    color: #444444 !important; /* 진한 회색 */
    font-weight: 600 !important; /* 글자 두께도 약간 굵게 */
    opacity: 1 !important;
  }

  /* (선택사항) 마우스 올렸을 때는 더 진하게 */
  nav[data-toggle="toc"] .nav-link:hover,
  .section-nav .toc-entry a:hover {
    color: #000000 !important; /* 완전 검정 */
  }

  /* 2. 본문 중간중간에 나오는 큰 연도 제목 */
  h2.year {
    color: #222222 !important; /* 거의 검정 */
    opacity: 1 !important;
  }
</style>
