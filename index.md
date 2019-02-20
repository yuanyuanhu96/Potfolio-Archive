---
layout: default
---
<head>
  <style>
   .project-icon{
   width: 100px;
   height: 100px;
   border:0px solid #ccc;
   float: left;
   box-sizing: border-box;
  }
   .project-text{
   margin-left: 135px;
   //margin-top: 50px;

  } 
    
   .pdf-icon{
   width: 100px;
   height: 200px;
   border:0px solid #ccc;
   box-sizing: border-box;
  }
  
  .Foot {
  height: 170px;
  float: left;
  //background: linear-gradient( #8CC5DF, #A7DAF1); /* 标准的语法 */
  background-color: #B1D3E2;
  min-width: 100%;
  text-align: center;
  color: #FFFFFF;
  padding-top: 40px;
  font-weight: lighter;
  margin-top: 10px;

}

  
  </style>
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
    <div>-</div>
    <span>Email. pyhu76@id.iit.edu  </span>

    <span>  Tel. (312)709-9034</span>

  </div>
  
</body>
