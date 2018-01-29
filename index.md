---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Gary2Luke</h1>
        <a href="http://weibo.com/2285663530/" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="50"/></a> 
        <a href="https://github.com/Gary2Luke/" target="_blank"><img src="https://github.com/favicon.ico" alt="" width="50"/></a>        
        <a href="https://www.facebook.com/profile.php?id=100007921934416" target="_blank"><img src="http://www.facebook.com/favicon.ico" alt="" width="50"/></a> 
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
