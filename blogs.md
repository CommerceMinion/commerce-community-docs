---
title: Blogs
layout: default
---

### Blog Posts from the Community

<ul>
    {% for blog in site.data.blogs %}
    <li>
        <a href="{{blog.link}}">
            {{ blog.title }}
        </a>
        by {{ blog.author }}
    </li>
    {% endfor %}
</ul>