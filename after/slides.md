---
title: Conference Slides
---
<section>
    <ul>
    {% for slide in site.data.slides %}
    <li>
    <a href="{{ slide.file }}">{{ slide.title }}</a> by {{ slide.speaker }} (File Type: {{ slide.file_type }})
    </li>
    {% endfor %}
    </ul>
</section>