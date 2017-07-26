---
title: Sitecore Commerce Community
layout: default
---



### Community Blogs

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

### Plugins

<ul>
    {% for plugin in site.data.plugins %}
    <li>
        <a href="{{plugin.link}}">
            {{ plugin.name }}
        </a>
    </li>
    {% endfor %}
</ul>

### Product Documentation

<ul>
    {% for doc in site.data.documentation %}
    <li>
        <a href="{{doc.link}}">
            {{ doc.title }}
        </a>
    </li>
    {% endfor %}
</ul>

### Demo Site & Reference Storefront

- [Retail Demo](https://github.com/Sitecore/Sitecore.Demo.Retail) (supports 8.2.1 initial release)
- [Reference Storefront](https://github.com/Sitecore/Reference-Storefront) (supports latest version)

### @CommerceMinion

Keep up to date with what's going on with Sitecore Commerce through [@commerceminion](https://twitter.com/commerceminion), including notifications for new forum posts

### Community Support

- [Sitecore Commerce Community Forums](https://community.sitecore.net/developers/f/6)
- [Join the #ecommerce channel on sitecorechat.slack.com](https://sitecorechat.slack.com/)
- [Sitecore Commerce on Stackexchange](https://sitecore.stackexchange.com/questions/tagged/sitecore-commerce)

