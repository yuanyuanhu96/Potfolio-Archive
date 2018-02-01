---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Yuanyuan Hu</h1>
        <a href="http://hu-yuanyuan.com/Hua-Xiao-Tuo" target="_blank"><img src="/images/Project-icon-png/1_favicon.ico" alt="" width="100"/></a>
        <a href="https://huyuanyuan96.github.io/carriage-return-line-feed-new-line-end-file" target="_blank"><img src="/images/Project-icon-png/Project-icon-02.png" alt="" width="100"/></a>
        <a href="https://huyuanyuan96.github.io/carriage-return-line-feed-new-line-end-file" target="_blank"><img src="/images/Project-icon-png/Project-icon-03.png" alt="" width="100"/></a>
                <a href="https://huyuanyuan96.github.io/eating-flow" target="_blank"><img src="/images/Project-icon-png/Project-icon-04.png" alt="" width="100"/></a>
                <a href="https://huyuanyuan96.github.io/wasa-bean" target="_blank"><img src="/images/Project-icon-png/Project-icon-05.png" alt="" width="100"/></a>
                <a href="https://huyuanyuan96.github.io/carriage-return-line-feed-new-line-end-file" target="_blank"><img src="/images/Project-icon-png/Project-icon-06.png" alt="" width="100"/></a>
                <a href="https://huyuanyuan96.github.io/Ada-bird" target="_blank"><img src="/images/Project-icon-png/Project-icon-07.png" alt="" width="100"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" target="_blank">{{ post.icon }}</a>    
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
