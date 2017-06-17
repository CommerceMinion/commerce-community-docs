---
title: Sitecore Commerce Community
layout: default
---

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

### Guides

<ul>
    {% for guide in site.data.guides %}
    <li>
        <a href="{{guide.link}}">
            {{ guide.title }}
        </a>
    </li>
    {% endfor %}
</ul>

### @CommerceMinion

Keep up to date with what's going on with Sitecore Commerce through [@commerceminion](https://twitter.com/commerceminion), including notifications for new forum posts

### Community

- [Sitecore Commerce Community Forums](https://community.sitecore.net/developers/f/6)
- [Join the #ecommerce channel on sitecorechat.slack.com](https://sitecorechat.slack.com/)

### Key Documentation

- [Official Documentation](https://doc.sitecore.net/sitecore_commerce)
- [Deployment Guide for Single Machine Install](http://commercesdn.sitecore.net/SitecoreCommerce/DeploymentGuide/en-us/index.html)
- [Developer's Guide](https://doc.sitecore.net/~/media/25566BB479844DB186DBEF2864246639.ashx)
- [PowerShell CmdLets for Managing Commerce Server Sites and Resources](http://commercesdn.sitecore.net/SCpbCS82/SitecoreCommerceGettingStarted/en-us/#DeploymentGuide/c_PowerShellCmdLets.html)
- [Commerce Connect Components](https://doc.sitecore.net/sitecore_commerce/commerce_connect_components?roles=all)

### Demo Site & Reference Storefront

- [Retail Demo](https://github.com/Sitecore/Sitecore.Demo.Retail) (supports 8.2.1 initial release)
- [Reference Storefront](https://github.com/Sitecore/Reference-Storefront) (supports latest version)
