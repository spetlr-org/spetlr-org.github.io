# Spetlr Homepage

A python SPark ETL libRary (SPETLR) for Databricks

Test!

{% include_relative /spetlr/readme.md %}

{% for thing in site.static_files %}
  {% if thing.path contains 'readme.md' %}
    Hello!
  {% endif %}
{% endfor %}


{% for thing in 'spetlr/docs' %}
  {{thing.path}}
{% endfor %}

{% for thing in 'spetlr/docs' %}
    {% include_relative thing.path/readme.md %}
{% endfor %}

