# This is tests:

<!---WIP: Include spetlr docs --->
{% for thing in "spetlr/docs" %}
  {{thing.content}}
{% endfor %}



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>



{{page.path}}
{{page.dir}}
{{page.url}}



{{ page.url | absolute_url }}

{% include_relative spetlr/README.md %}


