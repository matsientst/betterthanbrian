---
layout: page
username: matt_macchia
name: Matt Macchia
title: Matt Macchia
image: /assets/img/authors/matt-macchia.jpg
bio: Hands on tech leader, quickly builds and leads teams from idea to launch.   
---

 <div class="row">
    <div class="col-lg-4 offset-lg-4 col-md-6 text-center mb-30 mt-30">
        <div class="author-wrap">
            <div class="author-icon">
                {% if page.image %}
                    <img class="author-profile-image" src="{{ site.url }}{{ site.baseurl }}/{{ page.image }}" alt="{{ page.name }}">
                {% endif %}
            </div>
            <h4>{{page.name}}</h4>
            <p class="author-bio">{{ page.bio }}</p>
            <!-- <a href="{{service.url}}">Read More</a> -->
        </div>
    </div>
</div>