---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---
<style type="text/css">
.box {
        margin-bottom: 80px; /* 添加外边距，创建空白 */
        float: left; /* 可选，将元素浮动到左侧 */
}
.gallery {
        list-style: none;
        margin: 0;
        padding: 0;
}
.gallery li {
        padding: 10px;
        margin-right: 10px;
        margin-bottom: 50px;
        float: left;
        position: relative;
        width: 180px;
        height: 130px;
}
.gallery img {
        background: #fff;
        border: solid 1px #ccc;
        padding: 5px;
}
.gallery li:hover img {
        border-color: #999;
}
.gallery em {
        width: 102px;
        background: url(/images/bubble.gif) no-repeat;
        padding: 3px 0 6px;
        display: none;
        position: absolute;
        top: -2px;
        left: 50px;
        font-style: normal;
        text-align: center;
        color: blue;
}
.gallery a {
        text-decoration: none;
        color: #000;
}
.gallery a:hover em {
        display: block;
}
</style>

<div class="box">
<h1> Member </h1> <!-- 分块的名称-->
<ul class="gallery">
<li><a href="/images/bio-photo.jpg"><em>Abstract</em><img src="/images/bio-photo.jpg" alt="image" /></a></li> <!-- src是图片路径，em中间是悬浮在图片上现实的文本内容, a href是放大查看的图片-->
<li><a href="/images/bio-photo.jpg"><em>Ab</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
<li><a href="/images/bio-photo.jpg"><em>Abs</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
<li><a href="/images/bio-photo.jpg"><em>Abst</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
<li><a href="/images/bio-photo.jpg"><em>Abst</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
<li><a href="/images/bio-photo.jpg"><em>Abst</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
</ul>
</div>

<!-- div box重要，分割每个块-->
<div class="box"> 
<h1> Group </h1>
<ul class="gallery">
<li><a href="/images/bio-photo.jpg"><em>Abstract</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
<li><a href="/images/bio-photo.jpg"><em>Ab</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
<li><a href="/images/bio-photo.jpg"><em>Abs</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
<li><a href="/images/bio-photo.jpg"><em>Abst</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
<li><a href="/images/bio-photo.jpg"><em>Abst</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
<li><a href="/images/bio-photo.jpg"><em>Abst</em><img src="/images/bio-photo.jpg" alt="image" /></a></li>
</ul>
</div>