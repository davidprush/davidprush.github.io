---
layout: default
---
![Branching](/assets/images/banner-img.png)

[Link to another page](./another-page.html).

# Welcome to the website of David P. Rush the owner of Rush Solutions LLC.

<img src="/assets/images/thumbnail.png" width="100" height="100"/>

## A qualified IT consultancy providing business-enhancing IT solutions for small and growth-minded businesses:
<ul>
    <li> 
        Full-scale IT strategy
    </li>
    <li> 
        IT Modernization
    </li>
    <li> 
        New Technology Adoption
    </li>
    <li> 
        Business Process Integration
    </li>
    <li> 
        Audit of IT Environments, Applications, and infrastructures
    </li>
    <li> 
        Increased revenue through novel digital sales channels
    </li>
</ul>

## Blogs, Posts, Articles, & Stuff I'm thinking about...
<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
