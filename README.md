<!-- Include full content -->
{% capture content %}{% include index.md %}{% endcapture %}
{{ content | markdownify }}
