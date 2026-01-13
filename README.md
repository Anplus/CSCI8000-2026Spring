# CSCI8000 2026 Spring Paper Discussion

## Paper List

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date_to_string }}</span> » 
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
