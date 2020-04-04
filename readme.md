{% for item in site.github %}
    {{ item }}: {{ site.github[item] }}
{% endfor %}

{{ site.github.source.branch }}
