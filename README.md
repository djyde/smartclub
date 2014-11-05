结构
-----

> `header` 和 `footer` 为全局 layout，只需在 `container` 中填充内容即可。

**以下为渲染部份**

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
          <small>date</small><!-- 日期 -->
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

#####`index.html`: 首页Gallery
```html
<div id="slider">
      
      <ul class="pgwSlider">
        <!-- 以下规则请参照 http://pgwjs.com/pgwslider/ -->
        <li>
          <a href="#"> <!-- 跳转连接 -->
            <img src="http://ww1.sinaimg.cn/bmiddle/68f4ec25jw1elpp5gt970j21kw11xwpg.jpg">
            <span>SmartClub 华工站</span> <!-- 描述 -->
          </a>
        </li>

      </ul>
</div>
```