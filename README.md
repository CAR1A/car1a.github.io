---
permalink: /test
---
{% for file in site.static_files %}
- {{ file.path }} last edited at {{ file.modified_time | date:"%H:%m" }} with extname {{ file.extname }}{% endfor %}
