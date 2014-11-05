结构
-----

> `header` 和 `footer` 为全局 layout，只需在 `container` 中填充内容即可。

#####`history.html`: 历史活动页面(blog)

```html
<div class="post">
  <!-- 题图 -->
  <div id="image"><img src="static/images/test.jpg" /></div>
  
    <!-- 文本区域 -->
    <div id="text">
      <a href="#"> <!-- 文章地址 -->
        
        <div id="head">
          <p id="title">Title</p><!-- 标题 -->
          <p id="date">date</p><!-- 日期 -->
        </div>
      </a>
        
       <div id="content">
           <!-- 文章摘要 -->
       </div>
          
  </div>
        
  <span style="float: right">
    <a href="#">阅读全文</a>
  </span>
</div>
```

#####`post.html`: 正文

```html
<div class="post typo">
        <h1><!-- 标题 --></h1> 
        <p><small><!-- 日期 --></small></p> 
        <div class="typo post">
          <!-- 文章内容（已经 typo.css 格式化） -->
        </div>
</div>
```