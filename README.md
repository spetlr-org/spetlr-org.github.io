# Spetlr Homepage

A python SPark ETL libRary (SPETLR) for Databricks


{% for thing in spetlr/docs %}
  {% if thing.url contains 'README.md' %}
    {% include_relative thing %}
{% endif %}
{% endfor %}
