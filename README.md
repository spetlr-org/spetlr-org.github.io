# Spetlr Homepage

A python SPark ETL libRary (SPETLR) for Databricks

Test!


{% for thing in spetlr/docs %}
  {{thing.path}}
  {% if thing.path contains 'README.md' %}
    {% include_relative thing.path %}
    {{thing.path}}
  {% endif %}
{% endfor %}
