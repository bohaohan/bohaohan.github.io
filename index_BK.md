---
layout: home
---

<div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">
            <li class="on"><a href="/"><span>Project</span></a></li>
            <li style="text-align:center"><a href="/blog"><span>Blog</span></a></li>
            <li style="text-align:right"><a href="/cv.pdf"><span>CV</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.project %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    	<style>
    		.my {
    			width: 100%;
    			text-align: center;
    		}
    		.my img {
    			width: 150px;
    		}
    		.myimg {
    			width: 150px;
    			height: 150px;
    			overflow: hidden;
    			border-radius: 50%;
    			margin: 100px auto;
    			margin-bottom: 50px;
    		}
    	</style>
    	<div class = "my">
    		<div class = "myimg">
    			<img src = "/images/o.png" >
    		</div>
    		<div style="text-align: center;">
    			<p style = "color: #fff; font-size: 30px;">Haohan Bo</p>
    			<p style = "color: #9a9a9a;; font-size: 20px;">No pain, no gain.</p>
    		</div>
    	</div>
    </div>
</div>
