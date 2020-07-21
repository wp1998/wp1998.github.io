
# 不用翻页的列表：
{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) {{ page.date | date: '%B %d, %Y' }}
{% endfor %}