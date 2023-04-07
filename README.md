# Spetlr Homepage

A python SPark ETL libRary (SPETLR) for Databricks

Test!

{% for thing in site.static_files %}
  {% if thing.path contains 'readme.md' %}
    Hello!
  {% endif %}
{% endfor %}


{% for thing in spetlr/docs %}
  {{thing.path}}
{% endfor %}

{% for thing in spetlr/docs %}
  {{thing.content}}
  {% if thing.path contains 'README.md' %}
    {% include_relative thing.path %}
    {{thing.path}}
  {% endif %}
{% endfor %}

