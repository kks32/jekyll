---
layout: post
title: "Override Author Byline Test Post"
excerpt: "An article to test overriding the default site author."
categories: articles
tags: [sample-post, readability, test]
author: krishna_kumar
comments: true
share: true
image:
  feature: so-simple-sample-image-7.jpg
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
---

For those of you who may have content written by multiple authors on your site you can now assign different authors to each post if desired.

Previously the theme used a global author for the entire site and those attributes would be used in all bylines, social networking links, Twitter Card attribution, and Google Authorship. These `owner` variables were defined in `config.yml`

Start by modifying or creating a new `authors.yml` file in the `_data` folder and add your authors using the following format.

{% highlight yaml %}
# Authors

krishna_kumar:
  name: Krishna Kumar
  web: https://github.com/kks32
  email: kks32@cam.ac.uk

{% endhighlight %}

To assign Billy Rick as an author for our post. You'd add the following YAML front matter to a post:

{% highlight yaml %}
author: krishna_kumar
{% endhighlight %}