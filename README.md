# Spetlr Homepage

A python SPark ETL libRary (SPETLR) for Databricks

Test!

{% for thing in spetlr/docs %}
  {{thing.path}}
{% endfor %}

{% for thing in spetlr/docs %}
    {% include_relative thing.path/readme.md %}
{% endfor %}

