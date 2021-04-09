---
layout: default
---
![Branching](/assets/images/banner-img.png)

[Link to another page](./another-page.html).

# Welcome to the website of David P. Rush...

<img src="/assets/images/thumbnail.png" width="100" height="100"/>

This is a simple website where I post things I am thinking about.

## Blogs, Posts, Articles, & Stuff I'm thinking about...
<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
    </li>
    {% endfor %}
</ul>