---
layout: page
name: blog
---

## Blog

This is a reverse-chronological list of thoughts I have, in roughly real-time. I'm not a huge *blogger*, as it were, so this may be a little sparse, but if I'm ever in the mood here's where you'll find the results.

{% for post in site.posts %}
- [{{post.title}}]({{post.url}}), {{post.excerpt}}
{% endfor %} 
