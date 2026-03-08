---
layout: default
title: 關於
permalink: /about/
---

<div class="about-page">

  <div class="section-head">
    <span class="section-head-label">關　於　本　站</span>
    <span class="section-head-num">About</span>
  </div>

  <div class="about-wrap">
    <article class="about-body">

      <div class="about-ticket">
        <div class="ticket-top">
          <div>
            <p class="ticket-cat">個人簡介　/　PROFILE</p>
            <div class="ticket-id" aria-hidden="true">0001</div>
          </div>
          <div class="ticket-stamp">在　站</div>
        </div>
        <div class="ticket-tear"><div class="tear-line"></div></div>
        <div class="ticket-bottom">
          <h1 class="article-title">{{ site.name }}</h1>
          <div class="article-meta">
            <div>
              <span class="meta-field-label">所　在</span>
              <span class="meta-field-value">板橋，台灣</span>
            </div>
            <div>
              <span class="meta-field-label">主　題</span>
              <span class="meta-field-value">語言 · 翻譯 · 閱讀 · 日常</span>
            </div>
          </div>
        </div>
      </div>

      <div class="article-body">
        <p>這裡是 lin3310 的個人部落格。記錄關於語言、翻譯、閱讀和日常生活的各種思考與筆記。</p>

        <h2>關於這個站</h2>
        <p>部落格建立在 Jekyll + GitHub Pages 上，主題由自己設計，從台鐵硬票的設計語言與日式雜誌排版取得靈感。</p>

        <h2>聯絡</h2>
        <p>有任何想法或問題，歡迎透過 <a href="https://github.com/{{ site.github_username }}" target="_blank" rel="noopener">GitHub</a> 聯絡。</p>
      </div>

    </article>
  </div>

</div>

<style>
.about-page {
  max-width: var(--article-w);
  margin: 0 auto;
  padding: 3.5rem 2.5rem 5rem;
}
.about-ticket {
  border: 1px solid var(--rule-thick);
  border-radius: 2px;
  margin-bottom: 3rem;
  overflow: hidden;
}
</style>
