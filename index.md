{% for report in site.data.reports %}
- {{ report.Date }}

    **{{ report.Researcher }}** reported _{{ report.Vulnerability }}_
{% endfor %}
