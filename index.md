---
layout: home
---

<div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">
            <li class="on"><a href="/"><span>Blog</span></a></li>
            <li style="text-align:center"><a href="/opinion"><span>Opinion</span></a></li>
            <li style="text-align:right"><a href="/project"><span>Project</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.blog %}
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
    			margin: 80px auto;
    		}
    	</style>
    	<div class = "my">
    		<div class = "myimg">
    			<img src = "images/o.png" >
    		</div>
    	</div>
    </div>
</div>
