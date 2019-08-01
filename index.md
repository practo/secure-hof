{% for report in site.data.reports reversed %}
- {{ report.Date }}

    **{{ report.Researcher }}** reported _{{ report.Vulnerability }}_
{% endfor %}
