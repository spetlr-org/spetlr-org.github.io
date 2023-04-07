# Spetlr Homepage

A python SPark ETL libRary (SPETLR) for Databricks

Test!


{% for thing in spetlr/docs %}
  {{thing.content}}
  {% if thing.path contains 'README.md' %}
    {% include_relative thing.path %}
    {{thing.path}}
  {% endif %}
{% endfor %}


{% for image in site.static_files %}
    {% if image.path contains readme %}
        Hello!
    {% endif %}
{% endfor %}
