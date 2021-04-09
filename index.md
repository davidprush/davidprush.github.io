---
layout: default
---
### Welcome...

![Branching](/assets/images/banner-img.png)

[Link to another page](./another-page.html).

# Header 1
<img src="/assets/images/thumbnail.png" width="100" height="100"/>
This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

```
<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
```