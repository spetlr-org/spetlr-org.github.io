# Spetlr Homepage

A python SPark ETL libRary (SPETLR) for Databricks


{% for thing in spetlr/docs %}
  {% if thing.path contains 'README.md' %}
    {% include_relative thing.content %}
    {{thing.content}}
  {% endif %}
{% endfor %}
