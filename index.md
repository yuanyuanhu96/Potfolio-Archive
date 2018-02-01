---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Portfolio of</h1>
        <h1>Yuanyuan Hu</h1>
        <a href="http://HuYuanyuan96.github.io/Supplementary/Portfolio of Yuanyuan Hu.pdf" target="_blank"><img src="/images/Download-PDF.png" alt="" width="100"/></a>
      
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" target="_blank">{{ post.icon }}</a> <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
