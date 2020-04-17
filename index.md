日常学习过程中所遇到的一些问题和相关经验的总结

{% for post in site.posts %}

{{ post.date|date_to_string }} <a href='{{ site.baseurl }}{{ post.url }}'>{{ post.title }}</a>

{% endfor %}
