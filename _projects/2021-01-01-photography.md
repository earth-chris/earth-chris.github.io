---
title: 'Photography'
subtitle: 'From above and below'
date: 2021-01-02 00:00:00
description: Nature photography from the ground and from the sky.
featured_image: "/images/photography/amazon.jpg"
---

<div class="gallery" data-columns="3">
    {% for photo in site.data.photography %}
        <img src="{{ photo.src | relative_url }}">
    {% endfor %}
</div>
