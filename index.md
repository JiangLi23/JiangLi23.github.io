---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <img src="images/P51129-124527.jpg"/>
		<h1>Hi,I am JiangLi(蒋理) From NUAA 803Lab</h1>
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
