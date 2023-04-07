# Spetlr Homepage

A python SPark ETL libRary (SPETLR) for Databricks

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


{% include spetlr/docs/configuration.md %}

