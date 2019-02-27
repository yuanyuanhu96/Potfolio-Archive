---
layout: default
---
<head>

<head>

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
         <div class="Me">
      <h1>
        <span>Y</span>
        <span>U</span>
        <span>A</span>
        <span>N</span>
        <span>Y</span>
        <span>U</span>
        <span>A</span>
        <span>N</span>
        <span><br> <br/></span>
        <span>H</span>
        <span>U</span>
      </h1>
    </div>
        
   <div class="resume">
    <a class="resume-link" href="http://HuYuanyuan96.github.io/Resume_HU.pdf" target="_blank"> <img src="/images/Resume.svg" alt="" width="100"/></a>
   </div>
  </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
        <div class="project-icon">
          <a href="{{ post.url }}" target="_blank">{{ post.icon width="100"}}  </a>
        </div>
                <div class="project-text">
        <div class="project-title">
        <a href="{{ post.url }}" class="title">{{ post.title }}</a>
        </div>  
          <div class="title-desc">{{ post.description }}</div>
          </div>  
        </li>
        {% endfor %}
      </ul>
    </div>
    
  </div>
  
   <div class="Foot">
    <div>Thanks for your visiting</div>
    <div>Please feel free to contact me :)</div>
    <p> &nbsp;</p>
      <p> &nbsp;</p>

    <span>Email. yhu76@id.iit.edu  </span>
    <span>&nbsp;&nbsp;</span>
  <span>  Tel. (312)709-9034 </span>

  </div>
  
</body>
