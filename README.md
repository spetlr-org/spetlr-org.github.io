# Spetlr Homepage

A python SPark ETL libRary (SPETLR) for Databricks

Test!

{% for thing in spetlr/docs %}
  <h1>{{thing.path}}</h1>
{% endfor %}

{% for thing in spetlr/docs %}
    {% include_relative thing.path/readme.md %}
{% endfor %}

