---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Yuanyuan Hu</h1>
        <a href="http://hu-yuanyuan.com/Hua-Xiao-Tuo" target="_blank"><img src="/images/Project-icon-png/1_favicon.ico" alt="" width="50"/></a>
        <a href="https://huyuanyuan96.github.io/carriage-return-line-feed-new-line-end-file" target="_blank"><img src="/images/Project-icon-png/Project-icon-02.png" alt="" width="50"/></a>
                        <a href="http://instagram.com/beiyuu/" target="_blank"><img src="http://d36xtkk24g8jdx.cloudfront.net/bluebar/00c6602/images/ico/favicon.ico" alt="" width="50"/></a>
         <a href="http://instagram.com/beiyuu/" target="_blank"><img src="http://d36xtkk24g8jdx.cloudfront.net/bluebar/00c6602/images/ico/favicon.ico" alt="" width="50"/></a>
         <a href="http://instagram.com/beiyuu/" target="_blank"><img src="http://d36xtkk24g8jdx.cloudfront.net/bluebar/00c6602/images/ico/favicon.ico" alt="" width="50"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
