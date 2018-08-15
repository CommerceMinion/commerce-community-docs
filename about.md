---
title: About
layout: default
---

## Community-Driven Documentation

Sitecore Commerce is an integrated Experience Commerce solution built by Sitecore. This community site provides links to different resources for the commerce product, whether official Sitecore documentation or developer blog posts.

### Contribute

You are welcome to contribute your own content to the site, simply make the changes and submit a pull request. For now, submit content in the following areas:

- Blog Posts
- Commerce Engine Plugins or tools you've made
- Install Guidance

Contributing is done by adding an entry to one of the files in the _data folder.  

For example:  

**blogs.yml**

{% highlight yml %}
- title: Creating a Simple Bundle Promotion
  link: https://domain.com/blog-post
  author: author name
  submitted-by: your name
{% endhighlight %}

**plugins.yml**

{% highlight yml %}
- name: Shared Cart
  link: https://github.com/heardk/commerce-plugins
  author: author name
  submitted-by: your name
{% endhighlight %}

**install.yml**

{% highlight yml %}
- name: Setting up a Development Environment
  link: https://domain.com/blog-dev-environment
  author: author name
  submitted-by: your name
{% endhighlight %}

`documentation.yml` is reserved for highlighting official product documentation links. 

Follow Github's instructions on [creating a pull request](https://help.github.com/articles/creating-a-pull-request/), if you're not sure how to contribute.

### Official Documentation

This site is community-driven and not run by Sitecore. For official documentation, please visit the following:

- [Sitecore.net](https://sitecore.net)
- [Sitecore Commerce Docs](https://doc.sitecore.net/sitecore_commerce)
- [Sitecore Commerce Downloads](https://dev.sitecore.net/Downloads/Sitecore_Commerce.aspx)
