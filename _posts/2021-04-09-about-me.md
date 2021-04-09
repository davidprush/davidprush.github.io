---
layout: default
---

## Blogs, Posts, Articles, & Stuff I'm thinking about...
<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>